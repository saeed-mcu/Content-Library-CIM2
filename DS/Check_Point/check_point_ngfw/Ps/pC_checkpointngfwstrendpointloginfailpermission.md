#### Parser Content
```Java
{
Name = "checkpoint-ngfw-str-endpoint-login-fail-permission"
Vendor = "Check Point"
Product = "Check Point NGFW"
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Conditions = [
"""]: """
"""]["""
""" logged in with ReadWrite permission"""
]
Fields = [
  """\[({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?\]\[[^\]]*\]\[[^\]]*\]\[[^\]]*\]\s*<\d+>(({src_host}[\w\-.]+)\s+)?({process_name}.+?)\[({process_id}\d+)\]:\s*({additional_info}User\s+({user}[\w\.\-\!\#\^\~]{1,40}\$?)\s+logged in.*?)\s*$"""
  ]
ParserVersion = "v1.0.0"


}
```