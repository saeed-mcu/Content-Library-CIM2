#### Parser Content
```Java
{
Name = pan-ngfw-leef-alert-trigger-success-syslogintegration
  Vendor = Palo Alto Networks
  Product = Palo Alto NGFW
  TimeFormat = "MMM dd yyyy HH:mm:ss z"
  Conditions = [ """LEEF:""", """|Palo Alto Networks|PAN-OS Syslog Integration|""" ,"""|Severity="""]
  Fields = [
    """Severity=({alert_severity}[^\s|]+)""",
    """DeviceName =({host}[\w\-.]+)""",
    """LEEF:([^|]*\|){4}({alert_name}[^\|]+)""",
    """Subtype=({alert_type}[^\s\|]+)\s*\|""",
    """devTime=({time}[^\|]+)\s*\|""",
    """msg="({additional_info}[^"]+)"""",
    """sequence=({alert_id}\d+)""",
    """msg="(C|c)lient\s'({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})'""",
  ]
  ParserVersion = "v1.0.0"


}
```