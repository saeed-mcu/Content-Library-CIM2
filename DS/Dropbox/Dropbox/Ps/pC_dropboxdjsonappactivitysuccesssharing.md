#### Parser Content
```Java
{
Name = dropbox-d-json-app-activity-success-sharing
    Vendor = Dropbox
    Product = Dropbox
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ssZ"
    Conditions = [ """"event_category": "sharing"""", """"info_dict":""", """"event_type": "sf_request_access"""" ]
    Fields = [
      """"name":\s*"(?:N\/A|({full_name}[^"@,]+))"""",
      """"name":\s*"(?:N\/A|(({domain}[^"@\\\s]+)\\+)?({user}[^"@\\\s]+))"""",
      """"email":\s*"(?:N\/A|({email_address}[^@"\s]+@({email_domain}[^@"\s]+)))""",
      """"time":\s*"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d[\d:+-]+)"""",
      """"event_type":\s*"({operation}[^"]+)"""",
      """"event_type_description":\s*"({additional_info}[^"]+)"""",
      """"ip_address":\s*"({src_ip}[a-fA-F\d.:]+)""",
      """"folder_name":\s*"({object}[^"]+)""""
    ]
	ParserVersion = "v1.0.0"
  

}
```