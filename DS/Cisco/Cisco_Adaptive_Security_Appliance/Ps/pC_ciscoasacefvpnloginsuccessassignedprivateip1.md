#### Parser Content
```Java
{
Name = cisco-asa-cef-vpn-login-success-assignedprivateip-1
Vendor = "Cisco"
Product = "Cisco Adaptive Security Appliance"
TimeFormat = "epoch"
Conditions = [
  """CEF:"""
  """|CISCO|ASA|"""
  """|Assigned private IP address|"""
]
Fields = [
  """\srt=({time}\d+)"""
  """\sdst=({src_translated_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""
  """\sduser=({user}.+?)\s+\w+="""
  """\sdvc=({host}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""
  """\sdvchost=({host}[^\s]+)"""
  """\sad.Group=({realm}\w+)"""
]
DupFields = [
  "user->account"
]
ParserVersion = "v1.0.0"


}
```