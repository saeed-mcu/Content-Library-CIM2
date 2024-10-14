#### Parser Content
```Java
{
Name = fortinet-firewall-str-network-traffic-fail-deny-1
  Vendor = Fortinet
  Product = Fortinet Enterprise Firewall
  TimeFormat = "MMM dd HH:mm:ss"
  Conditions = [ """ Deny """, """ from """, """ to """, """ on interface """ ]
  Fields = [
    """({time}\w{3}\s+\d{1,2}\s+\d\d:\d\d:\d\d)\s""",
    """\s({host}[\w\-.]+)\sDeny """,
    """({action}Deny)(\s({direction}\w+))?\s({protocol}\w+)\s""",
    """\sfrom\s({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(\/({src_port}\d+))?\sto\s({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(\/({dest_port}\d+))?\s""",
    """\son interface\s({interface}[^\s"]+)"""
  ]
  ParserVersion = "v1.0.0"


}
```