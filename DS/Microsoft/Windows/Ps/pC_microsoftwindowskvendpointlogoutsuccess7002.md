#### Parser Content
```Java
{
Name = microsoft-windows-kv-endpoint-logout-success-7002
  ParserVersion = "v1.0.0"
  Conditions = [ """eventid="7002"""", """Microsoft-Windows-Winlogon""" ]
  Fields = ${WindowsParsersTemplates.windows-events-2.Fields}[
    """({event_name}User Logoff Notification for Customer Experience Improvement Program)""",
  ]

windows-events-2 = {
  Vendor = Microsoft
  Product = Windows
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)\.\d+Z\s*({host}[^\s]+)\s""",
    """eventid="+({event_code}\d+)""",
    """providername="+({provider_name}[^"]+)""",
    """userid="(?:[^\\]+\\+)?(SYSTEM|NETWORK SERVICE|({user}[^"]+))""",
    """\stask="+({operation}[^"]+)""",
    """\Weventrecordid="+({event_id}\d+)"""",
  ]
  DupFields = ["event_id->event_code"
}
```