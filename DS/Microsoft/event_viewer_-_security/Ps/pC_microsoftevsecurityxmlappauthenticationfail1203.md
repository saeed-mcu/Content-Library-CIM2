#### Parser Content
```Java
{
Name = microsoft-evsecurity-xml-app-authentication-fail-1203
  ParserVersion = "v1.0.0"
  Product = Event Viewer - Security
  Conditions = [ """>1203</EventID>""", """<TimeCreated SystemTime""" ]
  Fields = ${DLWindowsParsersTemplates.s-xml-events.Fields} [
    """<Computer>({host}[\w\-.]+?)<""",
# audit_type is removed
    """(<|&lt;)AuditResult(&gt;|>)({result}.+?)(&lt;|<)\/AuditResult(&gt;|>)""",
    """(<|&lt;)IpAddress(&gt;|>)({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
    """(<|&lt;)AuthProtocol(&gt;|>)(N\/A|({protocol}.+?))(&lt;|<)\/AuthProtocol(&gt;|>)""",
# proxy_server is removed
    """(<|&lt;)UserAgentString(&gt;|>)(N\/A|({user_agent}.+?))(<|&lt;)\/UserAgentString(&gt;|>)""",
    """(<|&lt;)Endpoint(&gt;|>)(N\/A|({endpoint}.+?))(<|&lt;)\/Endpoint(&gt;|>)""",
    """(<|&lt;)UserId(&gt;|>)(N\/A|({email_address}([A-Za-z0-9]+[!#$%&'+\/=?^_`~.-])*[A-Za-z0-9]+@({email_domain}[^\]\s"\\,;\|]+\.[^\]\s"\\,;\|]+))|(({domain}[^\\&]+)\\+)?({user}[\w\.\-\!\#\^\~]{1,40}\$?))(<|&lt;)\/UserId(&gt;|>)"""
    """(<|&lt;)FailureType(&gt;|>)(None|({failure_reason}.+?))(<|&lt;)\/FailureType(&gt;|>)""",
    """(<|&lt;)ErrorCode(&gt;|>)(N\/A|({error_code}.+?))(<|&lt;)\/ErrorCode(&gt;|>)""",
# relying_party is removed
    """(<|&lt;)Server(&gt;|>)(N\/A|({server}.+?))(<|&lt;)\/Server(&gt;|>)""",
# network_location is removed
    """<\d+>\w+ \d+ \d\d:\d\d:\d\d ({host}[\w_\-\.]+)"""
  ]

s-xml-events = {
  Vendor = Microsoft
  TimeFormat = [ "yyyy-MM-dd'T'HH:mm:ss.SSS", "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSSSZ", "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSZ" ]
  Fields = [
    """<TimeCreated SystemTime(\\)?=('|")({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{1,9}Z?)""",
    """<Message>({event_name}[^:<\.]+)""",
    """<Message>({event_name}[^<]+?)\.(\s|<)""",
    """<Message>({additional_info}[^<]+?)\s*<""",
    """<Message>Process ('|")?({process_name}[^\s'"]+)""",
    """<Security UserID(\\)?=('|")({user_sid}[^'"]+)""",
# update_path is removed
    """<Execution ProcessID(\\)?=('|")({process_id}[^'"]+)""",
    """<EventID[^<]*?>({event_code}\d+)""",
    """<Keyword>({result}[^<]+)<""",
    """<Data Name(\\)?=('|")ProcessName('|")>({process_path}({process_dir}[^<>]*?[\\\/]+)?({process_name}[^<>\\\/]+))</Data>""",
    """<Data Name\\*=('|")TargetProcessName('|")>({dest_process_path}({dest_process_dir}[^<>]*?[\\\/]+)?({dest_process_name}[^<>\\\/]+))</Data>""",
    """<Data Name(\\)?=('|")ProcessId('|")>({process_id}[^<]+?)\s*<""",
    """Security ID:\s*({user_sid}\S+)\s+Account Name:""",
    """Account Name:\s*(LOCAL SERVICE|-|({user}[\w\.\-\!\#\^\~]{1,40}\$?))\s+Account Domain:""",
    """Account Domain:\s*(NT AUTHORITY|-|({domain}\S+))\s+Logon ID:""",
    """Logon ID:\s*({login_id}\S+)\s+""",
    """Task Name:\s*(|-|({task_name}[^:]+?))\s*Task Content:""",
    """Client IP: ({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
    """ThreadID(\\)?=('|")({thread_id}\d+)"""
    """<Level>({run_level}[^<]+)<"""
  
}
```