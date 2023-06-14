#### Parser Content
```Java
{
Name = symantec-endpointprotection-json-alert-trigger-success-8040
  ParserVersion = "v1.0.0"
  Conditions = [ """type_id":8040,""",""""event_data_type":"sep"""",""""product_name":"Symantec Endpoint Security"""" ]
  Fields = ${SymantecParsersTemplates.json-symantec-endpoint-protection.Fields}[
    """"feature_name":"({alert_type}[^"]+)"""",
    """"policy":[^\}]+?"name":"({alert_name}[^"]+)""",
    """"severity_id":({alert_severity}\d+)""",
	  """"type_id":({event_code}8040)"""
  ]

json-symantec-endpoint-protection = {
    Vendor = Symantec
    Product = Symantec Endpoint Protection
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
    Fields = [
      """"time":"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)""",
      """"message":"\s*({additional_info}[^"]+)""",
      """"user_name":"(({domain}[^\\"]+)\\\\)?({user}[^"]+)""",
      """"uuid":"({user_uid}[^"]+)""",
      """"destinationServiceName":"({app}[^"]+)""",
      """"session_id":"({session_id}[^"]+)""",
      """"device_public_ip":"({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?"""",
      """"device_os_name":"({os}[^"]+)""",
      """"device_name":"({host}[\w\-.]+)""",
      """"device_domain":"({domain}[^"]+)""",
      """"rule_name":"({operation}[^"]+)"""
    
}
```