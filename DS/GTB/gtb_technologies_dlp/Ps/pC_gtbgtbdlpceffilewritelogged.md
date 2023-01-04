#### Parser Content
```Java
{
Name = gtb-gtbdlp-cef-file-write-logged
  ParserVersion = "v1.0.0"
  Conditions = [ """CEF:""", """|GTB|""", """|I/O Logged|I/O Logged Violation|""", """operation=Copy to LocalDrive act=Logged""", """src=Removable Media""" ]
  Fields = ${GTBParsersTemplates.cef-gtb-alerts.Fields}[
    """\Wfile=(({src_file_dir}[^=]*?[\\\/]+)?({src_file_name}[^\\\/=]+?(\.({src_file_ext}\w+))?))\s+\w+=""",
    """\Wdest=Local Drive:\s+"+(?:"+|({file_dir}[^=]*?[\\\/]+)?({file_name}[^\\\/=]+?(\.({file_ext}\w+))?))"+\s+\w+=""",
    """\Wdest=Local Drive:\s+"+\s*({file_path}(?:\w:|\\|\/)[^=]+?)"+\s+\w+="""
  ]

cef-gtb-alerts = {
    Vendor = GTB
    Product = GTB Technologies DLP
    TimeFormat = "epoch"
    Fields = [
      """\w+\s\d\d\s\d\d:\d\d:\d\d\s+({host}[\w-]+)""",
      """\Wrt=({time}\d{13})""",
      """\Wuser=({full_name}(({last_name}[^,=]+),\s+({first_name}[^=\(]+)\s+[^=]+|[^=]+))\s+\w+=""",
      """\Wcs5=({user}[^=]+)\s+\w+=""",
      """\Wcs6=({email_address}[^=@]+@[^=]+)\s+\w+=""",
      """\|GTB\|({dest_host}[^\|]+)\|""",
      """\Woperation=({operation}[^=]+)\s+\w+=""",
      """\WdeviceExternalId=({device_id}[^=]+)\s+\w+=""",
      """\Wcs7=({src_ip}[[A-Fa-f\d:.]+)\s+\w+=""",
      """\Wact=({action}[^=]+)\s+\w+=""",
      """CEF:[^\|]+\|GTB\|(?:[^\|]+\|){2}({alert_type}[^\|]+)?\|\s*({alert_name}[^\|]+)\|({alert_severity}\d+)\|"""
    ]
    DupFields = [ "operation->event_name" 
}
```