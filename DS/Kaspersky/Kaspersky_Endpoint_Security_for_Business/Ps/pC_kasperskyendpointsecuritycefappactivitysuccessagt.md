#### Parser Content
```Java
{
Name = kaspersky-endpointsecurity-cef-app-activity-success-agt
  ParserVersion = "v1.0.0"
  Vendor = Kaspersky
  Product = Kaspersky Endpoint Security for Business
  TimeFormat = "epoch"
  Conditions = [ """CEF:""", """|Kaspersky|""", """agt=""" ]
  Fields = [
    """\Wdvc=({host}[a-fA-F\d.:]+)""",
    """\Wrt=({time}\d+)""",
    """\WdeviceNtDomain=(|({domain}.+?))(\s+\w+=|\s*$)""",
    """CEF:([^\|]*\|){5}({alert_name}[^\|]+)\|({alert_severity}[^\|]+)""",
    """\Wcat=(|({alert_type}.+?))(\s+\w+=|\s*$)""",
    """\Wdhost=(|({dest_host}.+?))(\s+\w+=|\s*$)""",
    """\Wdst=({dest_ip}[a-fA-F\d.:]+)""",
    """\Wmsg=(|({additional_info}.+?))(\s+\w+=|\s*$)""",
    """Action:\s*({action}[^\\]+)""",
    """act=({action}[^\s]+?)\s*\w+=""",
    """fname=({file_path}({file_dir}[^=]*?[\\\/]+)?({file_name}[^\\\/=]+?(\.({file_ext}\w+))?))\s+\w+="""
    """requestClientApplication=({app}.+?)\s*\w+=""",
    """\Wdvchost=({src_host}[^\s]+)\s+\w+""",
    """eventId=({event_code}\d+)""",
    """externalId=({alert_id}\d+)""",
    """agt=({src_ip}[a-fA-F\d.:]+)\s"""
    """Object\\*Name:\s*({event_name}[^\r\n]+?)((\\r|\\n\\\t)|(\s+\w+=|\s*$))"""
    """User:\s*([^\\]+\\*)?(SYSTEM|({user}[^\s]+))""",
    """Result\\*Description:\s*({result}[^\\\s]+)"""
  ]


}
```