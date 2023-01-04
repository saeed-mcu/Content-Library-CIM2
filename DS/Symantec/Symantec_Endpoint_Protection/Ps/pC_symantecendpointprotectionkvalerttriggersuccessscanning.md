#### Parser Content
```Java
{
Name = symantec-endpointprotection-kv-alert-trigger-success-scanning
  Conditions = [ """vendor_product="Symantec Endpoint Protection"""", """Somebody is scanning your computer""" ]
  Fields = ${SymantecParsersTemplates.s-symantec-alert.Fields}[
    """Local_Host_IP_masked="({dest_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})""",
    """Remote_Host_IP_masked="({src_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})""",
  ]
  ParserVersion = "v1.0.0"

s-symantec-alert = {
    Vendor = Symantec
    Product = Symantec Endpoint Protection
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Fields = [
      """\sEnd_Time="({time}\d\d\d\d\-\d\d\-\d\d \d\d:\d\d:\d\d)""",
      """\sHost_Name =({host}[^,]+?)\s*(,|$)""",
      """\sdest=({dest_host}[^,]+?)\s*(,|$)""",
      """\suser=({user}[^,]+?)\s*(,|$)""",
      """\saction=({action}[^,]+?)\s*(,|$)""",
      """\ssignature="({alert_name}[^"]+)""",
      """\seventtype="?({alert_type}[^",]+)""",
      """\sseverity=({alert_severity}[^,]+?)\s*(,|$)""",
      """\sEvent_Description="({additional_info}[^"]+)""",
      """\sdest_port=({dest_port}\d+)""", 
    
}
```