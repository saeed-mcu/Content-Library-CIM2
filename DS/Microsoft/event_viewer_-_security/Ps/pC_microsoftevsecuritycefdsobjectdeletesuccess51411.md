#### Parser Content
```Java
{
Name = microsoft-evsecurity-cef-ds-object-delete-success-5141-1
    ParserVersion = v1.0.0
    Conditions = [ """CEF:""", """|Microsoft-Windows-Security-Auditing:5141|""", """A directory service object was deleted""" ]
    Fields = ${WindowsParsersTemplates.windows-events-3.Fields} [
      """({event_name}A directory service object was deleted)""",
      """({event_code}5141)""",
      """ad.DSType=({service_type}[^=]+?)\s[\w+\.]+=""",
      """cs6=({object_dn}[^"]+?)\s\w+=""",
      """cs5=({object_class}[^"]+?)\s\w+=""",
      ]

windows-events-3 = {
      Vendor = Microsoft
      Product = Event Viewer - Security
      TimeFormat = "epoch"
      Fields = [
        """\Wrt=({time}\d{13})""",
        """\sagt=({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
        """\Wdhost=\s*({dest_host}.+?)(\s+(\w+|\w+\.\w+)=|\s*$)""",
        """\sahost=({host}[^\s]+)""",
        """\Wdst=({dest_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?""",
        """\Wdntdom=({domain}.+?)(\s+(\w+|\w+\.\w+)=|\s*$)""",
        """\Wduser=\s*({user}.+?)(\s+(\w+|\w+\.\w+)=|\s*$)""",
        """\Wduid=(-|({login_id}[^=]+))\s\w+=""",
        """\WfilePath=(?:[\\\*]+)?({share_name}.+?)(\s+(\w+|\w+\.\w+)=|\s*$)""",
        """\Wad\.ShareLocalPath=(?:[\\\?]+)?(?:\s*|({share_path}({d_parent}.*?)({d_name}[^\\]+?))(\\+)?)(\s+(\w+|\w+\.\w+)=|\s*$)""",
        """\said=({aid}[^\s\\]+)""",
        """categoryOutcome=\/({result}[^\s]+)"""
        """Source Port(=|:)\s*({src_port}\d+)"""
        
}
```