#### Parser Content
```Java
{
Name = cisco-asa-str-app-activity-epm6
  ParserVersion = "v1.0.0"
  Conditions = [ """ %EPM-6-""" ]
  Fields = ${DLCiscoParsersTemplates.cisco-system-info.Fields}[
    """%EPM-6-({action}\w+):""",
  ]

cisco-system-info = {
  Vendor = "Cisco"
  Product = "Cisco Adaptive Security Appliance"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Fields = [
     """({time}\d+ \w+ \d+ \d+:\d+:\d+)\s+\w+:\s+\%""",
    """({event_code}%\w+\-[^:]+)""",
    """\%[\w+-.]+:\s*({additional_info}[^\$]+?)\s*$"""
  
}
```