#### Parser Content
```Java
{
Name = "microsoft-evsecurity-kv-ds-object-activity-success-5137"
Vendor = "Microsoft"
Product = "Event Viewer - Security"
TimeFormat = "MMM dd HH:mm:ss yyyy"
Conditions = [
  """MSWinEventLog"""
  """ 5137 Microsoft-Windows-Security-Auditing"""
  """A directory service object was created"""
]
Fields = [
  """({event_name}A directory service object was created)"""
  """({time}\w{3}\s\d{2}\s\d{2}:\d{2}:\d{2}\s\d{4})"""
  """(Information|Success Audit|Audit Success)\s+({host}[\w\-.]+)"""
  """({event_code}5137)"""
  """Subject:.+?Account Name:\s+({user}[\w\.\-\!\#\^\~]{1,40}\$?)\s+Account Domain:\s+({domain}.+?)\s+Logon ID:\s+({login_id}[^\s]+)"""
  """Object:.+?Class:\s+({object_type}.+?)\s+Operation:"""
  """Object:\s+DN:\s+({ds_object_dn}.+?)\s+GUID:"""
  """Object:\s+DN:.+?({ds_object_ou}OU.+?)\s+GUID:"""
]
DupFields = [
  "host->dest_host"
]
ParserVersion = "v1.0.0"


}
```