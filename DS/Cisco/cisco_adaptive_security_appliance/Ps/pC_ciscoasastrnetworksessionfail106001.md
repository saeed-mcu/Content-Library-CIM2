#### Parser Content
```Java
{
Name = cisco-asa-str-network-session-fail-106001
  ParserVersion = v1.0.0
  Vendor = Cisco
  Product = Cisco Adaptive Security Appliance
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """%ASA-""", """-106001""", """denied """ ]
  Fields = [
    """%ASA-({priority}\d+)-({event_code}\d+)""",
    """({event_name}Inbound ({protocol}\w+) connection ({result}denied))"""
    """\sfrom\s+(({src_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({src_host}[^\s]+?))\/({src_port}\d+)\s+to\s+(({dest_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({dest_host}[^\s]+?))\/({dest_port}\d+)\s""",
    """ on interface(\s+({dest_interface}\S+))?"""
  ]


}
```