#### Parser Content
```Java
{
Name = beyondtrust-powerbroker-str-process-create-success-messageforwarded
  Vendor = BeyondTrust
  Product = BeyondInsight
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """ Message forwarded from """, """: accepted """ ]
  Fields = [
    """\s+Message forwarded from ({host}[\w\-.]+)""",
    """accepted ({process_path}({process_dir}.+?[\\\/])?({process_name}[^\\\/]+?)) from ({user}[\w\.\-\!\#\^\~]{1,40}\$?)@({src_host}[\w\-.]+) to ({account}[^\s@]+)@({dest_host}[\w\-.]+)""",
  ]
  ParserVersion = "v1.0.0"


}
```