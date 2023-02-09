#### Parser Content
```Java
{
Name = google-cloudplatform-json-user-create-success-googleiamcreateserviceaccount
  TimeFormat = """yyyy-MM-dd'T'HH:mm:ss.SSSSSSZ"""
  ParserVersion = "v1.0.0"
  Conditions = [ """googleapis.com""", """"methodName":"google.iam.admin""", """CreateServiceAccount"""" ]
  Fields = ${GcpParserTemplates.gcp-cloudaudit-json.Fields}[
    """"service_account":.+"display_name":\s*"({account_name}[^"\\\/]+)"""",
    """"resource":.+"email_id":\s*"({account_email}[^"]+)"""",
  ]

gcp-cloudaudit-json = {
    Vendor = Google
    Product = Cloud Platform
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
    Fields = [
      """"timestamp":\s*"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z)""",
      """"logName"+:\s*"+({event_category}[^",\s\[\{]+)"+""",
      """"log-name"+:\s*"+({event_category}[^",\s\[\{]+)"+""",
      """"status":.+"code":\s*({result_code}\d+)""",
      """"status":.+"message":\s*({failure_reason}[^\\},]+)""",
      """"principalEmail":\s*"({user}[^"]+?@({domain}[^"@]+)|[^"]+)"""",
      """"callerIp":\s*"({src_ip}[^"]+)""",
      """"callerSuppliedUserAgent":\s*"({user_agent}[^"]+)""",
      """"methodName":\s*"({operation}[^"]+)""",
      """"resourceName":\s*"({resource}({resource_path}[^"]+)\/({resource_name}[^"\/]+))"""",
      """"serviceName":\s*"({service_name}[^"]+)""",
      """"resource":\s*\{\s*"type":\s*"({resource_type}[^"\\\/]+)"""",
      """"resource"+:[^\}]*labels[^\}]*"+project_id"+:\s*"+({project_id}[^"\\\/\}]+)"+""",
      """"resource"+:[^\}]*labels[^\}]*"+zone"+:\s*"+({zone}[^"\\\/\}]+)"+""",
      """"resource"+:[^\}]*labels[^\}]*"+location"+:\s*"+({region}[^"\\\/\}]+)"+""",
      """"resource"+:[^\}]*labels[^\}]*"+bucket_name"+:\s*"+({bucket_name}[^"\\\/\}]+)"+""",
      """"operation"+:[^\}]*first"+:\s*({operation_first}[^"\\\/\}\s,]+)""",
      """"operation"+:[^\}]*last"+:\s*({operation_last}[^"\\\/\}\s,]+)""",
    
}
```