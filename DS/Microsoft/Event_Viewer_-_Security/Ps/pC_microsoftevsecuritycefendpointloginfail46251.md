#### Parser Content
```Java
{
Name = microsoft-evsecurity-cef-endpoint-login-fail-4625-1
  ParserVersion = v1.0.0
  Vendor = Microsoft
  Product = Event Viewer - Security
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """CEF:""", """"eventID":"4625"""", """An account failed to log on""" ]
  Fields = [
    """"systemTime":"({time}\d+-\d+-\d+T\d+:\d+:\d+)""",
    """"computer":"({host}[\w\-.]+)""",
    """"message":"({event_name}[^"]+?)\s*"""",
    """"eventID":"({event_code}\d+)""",
    """"eventRecordID":"({event_id}\d+)""",
    """"severityValue":"({result}[^"]+?)\s*"""",
    """"status":"({result_code}[^"]+?)\s*"""",
    """"subStatus":"({result_code}[^"]+?)\s*"""",
    """"failureReason":"({failure_reason}[^"]+?)\s*"""",
    """"subjectUserSid":"({user_sid}[^"\s]+?)\s*"""",
    """"targetUserName":"({user}[^"\s]+?)\s*"""",
    """"targetDomainName":"({domain}[^"\s]+?)\s*"""",
    """"subjectLogonId":"({login_id}[^"\s]+?)\s*"""",
    """"logonType":"({login_type}\d+?)\s*"""",
    """"logonProcessName":"({auth_process}[^"]+?)\s*"""",
    """"authenticationPackageName":"({auth_package}[^"]+?)\s*"""",
    """"workstationName":"({src_host_windows}[^"]+?)\s*"""",
    """"ipAddress":"({src_ip}[A-Fa-f:\d.]+)""",
    """"ipPort":"({src_port}\d+)""",
  ]
  DupFields = [ 
    "host->dest_host" 
    "result_code->failure_code"
  ]


}
```