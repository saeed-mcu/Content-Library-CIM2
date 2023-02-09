#### Parser Content
```Java
{
Name = secureauth-login-kv-app-notification-success-92300
  ParserVersion = "v1.0.0"
  Conditions = [ """EventID="92300"""", """Timestamp=""", """Realm=""", """RequestID="""", """UserHostAddress=""" ]

secure-auth-events = {
  Vendor = SecureAuth
  Product = SecureAuth Login
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields =[
    """Timestamp="({time}\d+-\d+-\d+T\d+:\d+:\d+.\d+Z)""",
    """\WUserHostAddress="({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
    """\WRealm="({realm}[^"]+)""",
    """\WAppliance="({host}[\w\-.]+)""",
    """\WAppliance="({dest_host}[\w\-.]+)""",
    """\WUserID="({user}[^"]+)""",
    """\WPriority="({priority}\d+)""",
    """\WEventID="({event_code}\d+)""",
    """UserAgent="(?:-|Mozilla\/.+({os}iOS|Android|BlackBerry|Windows Phone|BeOS|(?:X|x)11|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin).+?({browser}Chrome|Safari|Opera|(?:F|f)irefox|MSIE|Trident))""",
    """Message="\s*({additional_info}[^"]+)\s*""""
  ]
 
}
```