#### Parser Content
```Java
{
Name = imsva-i-str-email-receive-fail-quarantinetransac
Vendor = "IMSVA"
Product = "IMSVA"
TimeFormat = "yyyy/MM/dd HH:mm:ss Z"
Conditions = [
  """ imsva"""
  """#null#"""
  """QuarantineTransac"""
]
Fields = [
  """\s({host}imsva\d+\s+[\w.\-]+)"""
  """({time}\d\d\d\d\/\d\d\/\d\d \d\d:\d\d:\d\d (\+|\-)\d\d:\d\d)\s+([^\s]+)(\s+[^\s]+){3,4}\s+({sender}[^\s@]+@[^\s@;]+)\s+(({email_recipients}({dest_email_address}[^\s@;]+@[^\s@;]+)[^\s]*)\s+)?\s*(|({email_subject}.+?))\s+(#null#|({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)\s+(.+?\[({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\])?"""  
  """\s({bytes}\d+)\s+bytes in """
  """\d\d\d\d \w+ \d\d \d\d:\d\d:\d\d (\+|\-)\d\d:\d\d\s+\d+\s+({email_attachments}({email_attachment}[^\s;]+)(;\s+[^;]+)*?)\s*$"""
]
DupFields = [ "sender->external_address" ]
ParserVersion = "v1.0.0"


}
```