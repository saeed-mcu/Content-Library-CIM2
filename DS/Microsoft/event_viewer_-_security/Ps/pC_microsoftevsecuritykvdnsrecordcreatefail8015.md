#### Parser Content
```Java
{
Name = microsoft-evsecurity-kv-dns-record-create-fail-8015
  Product = Event Viewer - Security
  ParserVersion = v1.0.0
  TimeFormat = "MM/dd/yyyy HH:mm:ss a"
  Conditions = [  """ EventCode=8015 """,""" ComputerName =""" ]
  Fields = ${WindowsParsersTemplates.windows-events.Fields}[
    """Primary Domain Suffix\s*:\s*({domain}\S+)""",
  ]

windows-events = {
  Vendor = Microsoft
  Product = Windows
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSSSZ"
  Fields = [
    """<Computer>({host}[\w.-]+)<\/Computer>""",
    """<\d+>\w+ \d+ \d\d:\d\d:\d\d ({host}[\w_\-\.]+)""",
    """<TimeCreated SystemTime\\*='({time}\d\d\d\d-\d\d\-\d\dT\d\d:\d\d:\d\d\.\d\d\d\d\d\d\d\d\dZ)'""",
    """<EventID>({event_code}\d+)<\/EventID>""",
    """<Message>({event_name}[^<\.]+)""",
    """<Keywords>({result}[^<]+)<\/Keywords>""",
    """<Task>({task}[^<]+)"""
  
}
```