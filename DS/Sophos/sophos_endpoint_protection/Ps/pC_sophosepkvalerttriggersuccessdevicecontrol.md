#### Parser Content
```Java
{
Name = sophos-ep-kv-alert-trigger-success-devicecontrol
Vendor = Sophos
Product = Sophos Endpoint Protection
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Conditions = [
  """Action="""
  """EventType=Device control;"""
  """ReportingName ="""
  """ComputerIPAddress="""
]
Fields = [
  """EventID=({alert_id}[\d]+);"""
  """EventTime=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)"""
  """EventType=({alert_name}[^;]+);"""
  """Action=({action}[^;]+);"""
  """UserName =([^\\]+\\+)?({user}[^;]+);"""
  """ReportingName =({additional_info}.+?);"""
  """({additional_info}SubType=[^;]+)"""
  """ComputerName =({src_host}[^;]+);"""
  """ComputerIPAddress=({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?"""
  """ComputerDomain=({domain}[^;]+)"""
]
DupFields = [
  "action->alert_severity"
]
ParserVersion = "v1.0.0"


}
```