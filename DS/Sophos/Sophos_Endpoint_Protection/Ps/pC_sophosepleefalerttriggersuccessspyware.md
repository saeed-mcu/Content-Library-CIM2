#### Parser Content
```Java
{
Name = sophos-ep-leef-alert-trigger-success-spyware
Vendor = Sophos
Product = Sophos Endpoint Protection
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Conditions = [
  """LEEF:1.0|Sophos|Enterprise Console|"""
  """|Viruses/spyware"""
]
Fields = [
  """EventID=({alert_id}[\d]+)"""
  """devTime=({time}\d{4}-\d{2}-\d{2} \d{2}:\d{2}:\d{2})"""
  """usrName =[^\\]*\\({user}.+?)\s+(\w+=|$)"""
  """LEEF:[^|]*\|Sophos\|Enterprise Console\|[^|]*\|({alert_name}[^|]*)\|"""
  """ReportingName =({alert_type}.+?)\s+(\w+=|$)"""
  """ComputerName =({src_host}.+?)\s+(\w+=|$)"""
  """src=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""
  """ActionName =({result}.*?)\s+\w+="""
]
ParserVersion = "v1.0.0"


}
```