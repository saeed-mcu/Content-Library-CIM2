#### Parser Content
```Java
{
Name = "crowdstrike-falcon-sk4-app-login-success-userauthenticate"
Conditions = [
""""event-name":""""
""""audit-event""""
""""OperationName":"userAuthenticate""""
]
ParserVersion = "v1.0.0"

leef-crowdstrike-alert-t.Fields} [
    """CrowdStrike\|([^|]+\|){2}({alert_name}[^|]+)""",
    """\WdocAccessedFileName =({file_name}[^|"]+?(\.({file_ext}[^"\|.]+?))?)\s*(\||\w+=|$|"+\s*$)""",
    """\WdocAccessedFilePath=({file_dir}[^=]+?)\s*(\||\w+=|$|"+\s*$)""",
    """\Wdescription=({additional_info}[^=]+?)\s*(\||\w+=|$|"+\s*$)"""
  
}
```