#### Parser Content
```Java
{
Name = accellion-kw-kv-email-send-success-withfiles
  ParserVersion = v1.0.0
  Product = Kiteworks
  Vendor = Accellion
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ 
    """Activity: Sent e-mail""", 
    """with files""" 
  ]
  Fields = [
    """\w+\s+\d+ \d+:\d+:\d+\s+({host}[\w.\-]+)\s+""",
    """({email_address}[^@\s]+@[^\s]+)\s+id=[^,]+,\s*({src_ip}[a-fA-F\d.:]+),\s*Activity:""",
    """\sSubject:\s*"*\s*({email_subject}[^"]+)\s*"*""",
    """\sTo:\s*({email_recipients}.+?)\s*with files \[({email_attachment}.+?({file_ext}\w+))\]""",
    """\sTo:\s*({dest_email_address}[^,@]+@[^\s,]+)"""
  ]


}
```