#### Parser Content
```Java
{
Name = github-g-kv-http-request-githubunicorn
  ParserVersion = v1.0.0
  Vendor = GitHub
  Product = GitHub
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSZ"
  Conditions = [ """service.name="github-unicorn"""", """ request_method="""", """ request_category="""" ]
  Fields = [
    """\sTimestamp="({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d.\d\d\d\d\d\dZ)""",
    """({host}\S+)\s+github-unicorn""",
    """\suser="(?:nil|({user}[\w\.\-\!\#\^\~]{1,40}\$?))"""",
    """\saction="({operation}[^"]+)""",
    """\sremote_address="({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
    """\srequest_host="(?:({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?|({dest_host}[^"]+))""",
    """\suser_agent="({user_agent}[^"]+)"""",
    """\sstatus="({http_response_code}\d+)""",
    """({app}github)""",
    """\saccept="({mime}[^"]+)""",
    """\sreferer="({referrer}[^"]+)""",
    """\surl="({url}[^"]+)""",
    """\sservice.name="({service_name}[^"]+)""",
    """\sgh.auth.type="({auth_method}[^"]+)""",
    """\senduser.scope="({authorization_scope}[^"]+)""",
    """\srequest_method="({method}[^"]+)""",
    """\scontent_type="({mime}[^"]+)"""
  ]


}
```