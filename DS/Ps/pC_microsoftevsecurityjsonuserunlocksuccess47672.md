#### Parser Content
```Java
{
Name = "microsoft-evsecurity-json-user-unlock-success-4767-2"
ExtractionType = json
Conditions = [
"""A user account was unlocked"""
"""Account Name:"""
"""computer_name"""
"""event_id":4767"""
]
ParserVersion = "v1.0.0"

json-windows-events-1.Fields}[
    """"(?:winlog\.)?computer_name"+:"+({src_host}[\w\-.]+)""",
    """"hostname"+:"+({host}[\w\-.]+)""",
    """exa_json_path=$.winlog.computer_name,exa_field_name=src_host""",
    """exa_json_path=$.host.hostname,exa_field_name=host""",
    """({event_name}A user account was disabled)""",
    """"hostname"+:"+(\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3}|({host}[^"]+))""",
  
}
```