#### Parser Content
```Java
{
Name = microsoft-mssql-leef-database-login-success-18453
  Conditions = [ """LEEF""", """ 18453 """, """Login succeeded""", """application=MSSQL""" ]
  Fields = ${MicrosoftParserTemplates.leef-mssql-login.Fields} [
    """({event_name}Login succeeded)""",
  ]
ParserVersion = "v1.0.0"

leef-mssql-login = {
    Vendor = Microsoft
    Product = MSSQL
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ssZZZ"
    Fields = [
      """devTime=({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\w{1,3})""",
      """resource=({host}[^=]+?)\s\w+=""",
      """LEEF\s({event_code}\d+)""",
      """usrName =(N\/A|(({domain}[^\\\s]+)\\+)?({user}[^\s]+))""",
      """message=({additional_info}[^\[]+)\.\s+\[""",
      """message=[^']+?\Wuser\s'(({domain}[^\\']+)\\+)?({user}[^']+)""",
      """CLIENT:\s+({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
      """application=({app}[^=]+?)\s+\w+="""
    ]
    DupFields = ["host->dest_host"
}
```