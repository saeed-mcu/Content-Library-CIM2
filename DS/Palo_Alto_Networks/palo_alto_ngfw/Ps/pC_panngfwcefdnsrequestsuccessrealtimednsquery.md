#### Parser Content
```Java
{
Name = pan-ngfw-cef-dns-request-success-realtimednsquery
  Vendor = "Palo Alto Networks"
  Product = "Palo Alto NGFW"
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Conditions = [ """CEF:""", """|palo alto networks|LF|""", """|DNS|realtime_dns_query|""" ]
  Fields = [
    """\srt=({time}\w{3}\s\d\d\s\d\d\d\d\s\d\d:\d\d:\d\d)\s""",
    """\sPanOSDNSResolverIP=({dest_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))"""
  ]
  ParserVersion = v1.0.0


}
```