#### Parser Content
```Java
{
Name = unix-ad-kv-process-create-fail-syscall
  ParserVersion = v1.0.0
  Vendor = Unix
  Product = Unix Auditd
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSS"
  Conditions = [
"""type=SYSCALL""",
"""success=no""",
"""msg=audit""",
"""audispd:"""
  ]
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\d)""",
    """exe=\"({process_path}[^\"]*)\"""",
    """exe=\"({process_dir}.+\/)({process_name}.+?)\"""",
    """\d\d:\d\d\s+({host}[\w\-.]+)\s+""",
    """\sppid=({parent_process_id}.+?)\s+(\w+=|$)""",
    """\spid=({process_id}.+?)\s+(\w+=|$)""",
    """\suid=({user_id}.+?)\s+(\w+=|$)""",
    """\sgid=({group_id}.+?)\s+(\w+=|$)""",
    """\sauid=({account_id}.+?)\s+(\w+=|$)""",
    """\sses=({session_id}\d+)\s+(\w+=|$)""",
    """\stype=({operation_type}.+?)\s+(\w+=|$)""",
    """\skey="({failure_reason}[^"]+)""""
  ]
  DupFields = [ "host->dest_host" ]


}
```