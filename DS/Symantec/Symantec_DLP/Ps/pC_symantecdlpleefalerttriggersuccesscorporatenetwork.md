#### Parser Content
```Java
{
Name = symantec-dlp-leef-alert-trigger-success-corporatenetwork
  Vendor = Symantec
  Product = Symantec DLP
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """LEEF:""", """|Symantec|DLP|""", """Corporate Network""" ]
  Fields = [
    """\s({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)[\+\-]\d+:\d+\s""",
    """\s({host}[\w\-.]+)\s+LEEF:""",
    """LEEF:([^\|]*\|){3}({alert_severity}\d+)""",
    """LEEF:([^\|]*\|){4}(N\/A)*.*?({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
    """({alert_name}(On|Off) the Corporate Network)""",
    """\d+:\d+:\d+\s+(AM|PM|am|pm)\s*HTTP\s*({malware_url}[^\s]+)""",
    """\d+:\d+:\d+\s+(AM|PM|am|pm)\s*(N\/A)*\s*((N\/A)|({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}))\s*({dest_host}\w\w\-\w+\d\d+)""",
  ]
  ParserVersion = "v1.0.0"


}
```