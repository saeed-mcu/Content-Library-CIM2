#### Parser Content
```Java
{
Name = unix-unix-str-endpoint-login-fail-sshfail
  ParserVersion = v1.0.0
  Vendor = "Unix"
  Product = "Unix"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """ssh: failed login attempt for """ ]
  Fields = [
    """\w+\s+\d+\s+\d+:\d+:\d+\s+({host}[\w\-.]+)\s+"""
    """Message forwarded from ({host}[^\s:]+)"""
    """({event_code}ssh)"""
    """failed login attempt for ({user}[^\s]+) from (({src_ip}[A-Fa-f:\d.]+)|({src_host}[\w\-.]+))\s*"""
  ]
  ParserVersion = "v1.0.0"


}
```