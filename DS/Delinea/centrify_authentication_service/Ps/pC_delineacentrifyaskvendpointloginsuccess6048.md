#### Parser Content
```Java
{
Name = "delinea-centrifyas-kv-endpoint-login-success-6048"
Vendor = "Delinea"
Product = "Centrify Authentication Service"
TimeFormat = "MM/dd/yyyy HH:mm:ss a"
Conditions = [
  """SourceName =Centrify AuditTrail"""
  """AUDIT_TRAIL|Centrify Suite|DirectAuthorize - Windows|"""
  """|PowerShell remote connection success|"""
  """EventCode=6048"""
]
Fields = [
  """:\d\d\s\w+\s*({time}\d\d\/\d\d\/\d\d\d\d\s\d\d:\d\d:\d\d\s(?i)(AM|PM))"""
  """ComputerName =({dest_host}[^\.]+)\.({domain}[^\s]+)"""
  """User=(NULL|NOT_TRANSLATED|({user}[\w\.\-\!\#\^\~]{1,40}\$?))"""
  """Sid=({user_sid}[^\s]+?)\sSidType"""
  """EventCode=({event_code}6048)"""
  """AUDIT_TRAIL\|Centrify Suite\|DirectAuthorize - Windows[^=]+?({event_name}PowerShell remote connection success)"""
  """Message:\s*({additional_info}[^:]+)\.\s+"""
]
ParserVersion = "v1.0.0"


}
```