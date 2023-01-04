#### Parser Content
```Java
{
Name = microsoft-evsecurity-kv-endpoint-login-fail-4771-3
  Vendor = Microsoft
  Product = Event Viewer - Security
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """Kerberos Authentication Service""", """Microsoft-Windows-Security-Auditing""","""ServiceName:""", """TicketOptions:""", """4771"""]
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)\.\d{1,3}[+\-]+\d\d:\d\d""",
    """({host}[^\s]+)\s+Kerberos Authentication Service""",
    """({event_code}4771)""",
    """TargetUserName:({user}[^,]+),""",
    """TargetSid:({user_sid}[^,]+),""",
    """ServiceName:\w+\/(?=\w)({domain}[^,]+)""",
    """Status:({result_code}[^,]+),""",
    """IpAddress:(::ffff:)?({dest_ip}[a-fA-F\d:.]+),""",
    """({result}(Success|Failure) Audit)"""
  ]
  DupFields = [
    "result_code->failure_code"
  ]
  ParserVersion = "v1.0.0"


}
```