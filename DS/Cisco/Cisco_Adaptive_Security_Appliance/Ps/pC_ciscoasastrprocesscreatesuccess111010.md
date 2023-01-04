#### Parser Content
```Java
{
Name = cisco-asa-str-process-create-success-111010
  ParserVersion = v1.0.0
  Vendor = Cisco
  Product = Cisco Adaptive Security Appliance
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Conditions = [ """-111010""", """%ASA-""" ]
  Fields = [
   """({time}\w+ \d+ \d{4} \d\d:\d\d:\d\d)""",
    """%ASA\-({priority}\d+)\-({event_code}\d+)""",
    """User\s+'({user}[^']+)'""",
    """({event_name}executed)\s+'({process_command_line}[^']+)\s*'""",
    """from IP ({src_ip}[a-fA-F0-9.:]+)"""
  ]


}
```