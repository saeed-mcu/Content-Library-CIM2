#### Parser Content
```Java
{
Name = microsoft-azure-sk4-app-file-success-secretget
  ParserVersion = v1.0.0
  Product = Azure Monitor
  Conditions= [ """ResourceId":"""", """"OperationName":"SecretGet"""", """"ResourceType":""" ]
  Fields = ${MSParsersTemplates.cef-microsoft-app-activity.Fields}[
    """"+clientInfo_s"+:\s*"+({user_agent}[^"]+)"+""",
    """"ResourceId":"({object}[^",]+)""""
  ]
  DupFields = [ "src_file_name->file_name" ]

cef-microsoft-app-activity = {
  Vendor = Microsoft
  Product = Azure Monitor
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z) [\w\-.]+ """,
    """"Host":"({host}[^"]+)"""",
    """"message":"({additional_info}[^"]+)""",
    """"description":"({additional_info}[^"]+)""",
    """category":"({category}[^"]+)"""",
    """Namespace:\s*(|({event_hub_namespace}[^\]]+?))\s*[\];]""",
    """EventHub name:\s*(|({event_hub_name}[^\]]+?))\s*\]""",
    """"resourceId":\s*"({object}[^"]+)""",
    """"Operation":\s*"({operation}[^"]+)""",
    """"operationName":"({operation}[^"]+)""",
    """"name":"({full_name}[^"]+)"""",
    """action":"({action}[^"]+)""",
    """"((?i)callerIpAddress|CIp)":"({src_ip}((\d{1,3}\.){3}\d{1,3}|[A-Fa-f\d]+:[a-fA-F\d:]+))(:({src_port}\d+))?"""",
    """claims\/(name|upn)":\s*"({email_address}[^@]+@[^"]+)""",
    """"email":"({email_address}[^\s@"]+@[^\s@"]+)""",
    """({app}Databricks)""",
    """"serviceName\\*":\\*"({app}[^"]+)""",
    """destinationServiceName =({app}[^=]+)\s+(\w+=|$)""",
# port is removed
    """"(?i)userAgent":"({user_agent}[^"]+)"""",
    """"statusCode\\":({http_response_code}\d+)""",
    """"actionName":"({operation}[^"]+)""",
    """(?i)userId":"(({email_address}[^@"]+@[^"]+)|({user_id}[^"]+))""",
    """\[Namespace:\s*({host}\S+) ; EventHub name:"""
    """"UserType":"*({user_type}[^,]+)"""
    """"Platform":"({os}[^"]+)""""
    """"OriginatingServer":"({src_host}({host}\w+))\s*(\([^\)]+?\))?(\\r\\n)?""""
    """"ClientInfoString":"({user_agent}[^"]+)","""
    """"BrowserName":"({browser}[^"]+)"""
    ]
  DupFields = [ "object->resource" 
}
```