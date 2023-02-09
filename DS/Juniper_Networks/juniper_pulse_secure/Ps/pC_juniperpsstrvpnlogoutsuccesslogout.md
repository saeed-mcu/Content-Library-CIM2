#### Parser Content
```Java
{
Name = juniper-ps-str-vpn-logout-success-logout
    ParserVersion = v1.0.0
    Vendor = Juniper Networks
    Product = Juniper Pulse Secure
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Conditions = [
""" Logout from """
""" (session:"""
]
    Fields = [
      """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d) \- .*?Logout from""",
      """(Juniper|PulseSecure):\s*({time}\d\d\d\d\-\d\d\-\d\d \d\d:\d\d:\d\d)\s+\-\s+({host}[\w\-.]+)""",
      """\d\d:\d\d:\d\d\s*({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\s*""",
      """\[\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}\]\s+(?:({email_address}[^@\s]+@[^@\s\(]+)|({user}[^\(\s]+))""",
      """PulseSecure:.*?\[({src_ip}[a-fA-F:\d.]+)\]\s+(({domain}[^\\]+)\\)?(?:({email_address}[^@\s]+@[^@\(]+)|({user}[^\s\\]+))\(({realm}[^\)]+)?""",
      """Logout from ({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?"""
    ]
    DupFields = [ "host->dest_host" ]
  

}
```