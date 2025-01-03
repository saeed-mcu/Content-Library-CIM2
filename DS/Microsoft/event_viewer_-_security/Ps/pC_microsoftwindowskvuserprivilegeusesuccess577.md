#### Parser Content
```Java
{
Name = microsoft-windows-kv-user-privilege-use-success-577
  Vendor = Microsoft
  Product = Event Viewer - Security
  ParserVersion = "v1.0.0"
  TimeFormat = "MMM dd HH:mm:ss yyyy"
  Conditions = [ "\t577\t", "Privileged Service Called:" ]
  Fields = [ 
    """({event_name}Privileged Service Called)""",
    """\s+(Mon|Tue|Wed|Thu|Fri|Sat|Sun) ({time}\w+ \d+ \d+:\d+:\d+ \d+)\s+""",
    """\s+(Information|Audit Success|Success Audit)\s+({host}[^\s]+)""",
    """({event_code}577)""",
    """Security\t([^\s]+\t){2}({result}.+?)\t""",
    """(?:Information|Audit Success|Success Audit).+?Primary User Name:\s+({user}[\w\.\-\!\#\^\~]{1,40}\$?)\s+Primary Domain""",
    """\s+Primary Domain:\s+({domain}[^\s]+)""",
    """\s+Primary Logon ID:\s+\([^,]+,({login_id}[^)]+)""",
    """\s+Privileges:\s+({privileges}.+?)\s+\d+""",
    """\s+({ownership_privilege}SeTakeOwnershipPrivilege)""",
    """\s+({environment_privilege}SeSystemEnvironmentPrivilege)""",
    """\s+({debug_privilege}SeDebugPrivilege)""",
    """\s+({tcb_privilege}SeTcbPrivilege)"""
  ]
  DupFields = [ "host->dest_host" ]


}
```