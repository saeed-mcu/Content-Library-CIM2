#### Parser Content
```Java
{
Name = "cisco-fp-csv-alert-trigger-success-primarydetectionengine"
Vendor = "Cisco"
Product = "Cisco Firepower"
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Conditions = [
  """Access Control Rule Name:"""
  """[Primary Detection Engine"""
]
Fields = [
  """\s(({host}[\w.\-]+))\s+([-\s:]+)?%FTD"""
  """Access Control Rule Name:\s*({alert_name}[^,]+)"""
  """Application Protocol:\s*({alert_type}[^,]+)"""
  """Access Control Rule Action:\s*({alert_severity}[^,]+)"""
  """User:\s*(?:Unknown|({user}[\w\.\-\!\#\^\~]{1,40}\$?))"""
  """({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}):({src_port}\d+) -> ({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\:({dest_port}\d+)"""
  """URL:\s*({malware_url}[^,]+)"""
  """Web App:\s(Unknown|({process_name}[^,]+))"""
]
SOAR {
  IncidentType = "malware"
  DupFields = [
    "time->startedDate"
    "vendor->source"
    "rawLog->sourceInfo"
    "alert_name->malwareName"
    "alert_type->malwareCategory"
    "alert_severity->sourceSeverity"
    "src_ip->malwareVictimHost"
    "malware_url->malwareAttackerUrl"
    "dest_ip->malwareAttackerIp"
  ]
  NameTemplate = "Cisco Sourcefire Alert ${alert_name} found"
  ProjectName = "SOC"
  EntityFields = [
    {
      EntityType = "device"
      Name = "src_address"
      Fields = [
        "src_ip->ip_address"
      ]
    

}
```