#### Parser Content
```Java
{
Name = microsoft-evdfsrep-kv-ds-replication-start-fail-5008
  Vendor = Microsoft
  Product = Event Viewer - DFS-Replication
  ParserVersion = "v1.0.0"
  Conditions = [   """SourceName =DFSR""", """EventCode=5008""" ]
  Fields = ${DLWindowsParsersTemplates.windows-system-info-2.Fields}[
    """ComputerName =({host}[\w\-.]+)"""
  ]

windows-system-info-2 = {
  Vendor = Microsoft
  ParserVersion = "v1.0.0"
  TimeFormat = "MM/dd/yyyy hh:mm:ss a"
  Fields = [
    """({time}\d\d\/\d\d\/\d\d\d\d\s\d\d:\d\d:\d\d\s((?i)AM|PM))""",
    """EventCode=({event_code}\d+)""",
    """EventType=({result}\d+)""",
    """TaskCategory=(None|({operation_type}[^\n]+?))\s*\w+(=|:)""",
    """Message=({additional_info}[^\n]+?)\s*\n"""

}
```