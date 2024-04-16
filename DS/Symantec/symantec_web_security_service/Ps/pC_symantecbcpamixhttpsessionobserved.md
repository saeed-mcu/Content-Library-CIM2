#### Parser Content
```Java
{
Name = "symantec-bcpa-mix-http-session-observed"
  ParserVersion = "v1.0.0"
  Vendor = Symantec
  Product = Symantec Web Security Service
  TimeFormat = ["yyyy-MM-dd HH:mm:ss","yyyy-MM-dd'T'HH:mm:ss", "yyyy-MM-dd'T'HH:mm:ssZ","yyyy-MM-dd'T'HH:mm:ss.SSSZ"]
  Conditions = [
    """ OBSERVED """
    """ TCP_"""
  ]
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d.\d\d\dZ)\s*""",
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\dZ)\s*({host}[\w\-.]+)\s*(\w+[\s\d]+?)?({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))\s*(-|(\d{1,3}\.){3}\d{1,3}|({user}[\w\.\-]{1,40}\$?)\s).*?"\s({method}[^\s]+)\s+({protocol}[^\s]+)\s+(?:-|({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({web_domain}[^\s]+))\s+(?:-|({dest_port}\d+))\s+.*?({action}OBSERVED)\s+(?:-|\\?"(none|({categories}({category}[^\\";]+)[^"]*?))\\?")\s+"""
    """dvchost=(-|({host}[^\s]+))\s\w+=""",
    """"({user_agent}Mozilla[^"]+?)\\?"\s\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3}\s\d+\s\d+"""
    """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)\s+\d+\s+(?:-|({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)\s+(\S+\s+)?(?:-|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}|\d+|TUNNELED|DENIED|FAILED|({user}[\w\.\-]{1,40}\$?))\s""",
    """\s\d+\s({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))\s+(-|non-interactive-user|({email_address}[^@\s]+@[^\.\s]+\.[^\s]+)|((({domain}[^\\\s]+)\\+)?({user}[\w\.\-]{1,40}\$?)))\s+([^\s]+\s){2}({action}OBSERVED)""",
    """({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))\s([^\s]+\s){3}({action}OBSERVED)""",
    """({action}OBSERVED)\s+(?:-|"(-|none|({categories}({category}[^",;:]{1,30})[^"]*?))")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+((?:({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?)\s+)?(?:-|({protocol}[^\s]+))\s+(?:-|({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({web_domain}[^\s]+))\s+(?:-|({=dest_port}\d+))\s+(?:-|\/|({uri_path}[^\s]+))\s+(({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))\s+)?(?:-|({uri_query}[^\s]+))\s+\S+\s+(?:-|"({user_agent}[^"]+?)\\?")\s+(?:-|({host}[^\s]+))\s+(?:-|({bytes_out}\d+))\s+(?:-|({bytes_in}\d+))\s+("*[^"]*"*\s+){3}(?:-|({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4})))\s+""",
    """({action}OBSERVED)\s+(?:-|\\?"(-|none|({categories}({category}[^",;:]{1,30})[^"]*?))\\?")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+(?:-|({protocol}[^\s]+))\s+(?:-|({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({web_domain}[\w\-.]+))\s+(?:-|0|({dest_port}\d+))\s+(?:-|\/|({uri_path}\/[^\s]*?))\s+(?:-|({uri_query}[^\s]+))\s+\S+\s+(?:-|\\?"*({user_agent}[^"]+?)\\?"*)\s+(?:-|({host}[^\s]+))\s+(?:-|({bytes_out}\d+))\s+(?:-|({bytes_in}\d+))\s+("*[^"]*"*\s+){5}(?:-|({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4})))\s+""",
    """\s({http_response_code}\d+)\s+({proxy_action}\S+)\s+({bytes_out}\d+)\s+({bytes_in}\d+)\s+(unknown|({method}\S+))\s+({protocol}\S+)\s+({web_domain}\S+)\s+(-|({url}(({=protocol}[^:\\\/\s,"]+):[\\\/]+)?[\\\/]*(({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({=web_domain}[^\\\/\s:,"]+))(:({dest_port}\d+))?(\/|({uri_path}\/[^\s\?",]*))?({uri_query}\?[^"\s]*)?))\s+(-|({user}[\w\.\-]{1,40}\$?))\s+\S+\s+(({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({=web_domain}[\w\-.]+))\s+(-|({mime}\S+))\s+"({user_agent}[^"]+?)\\?"\s+({action}OBSERVED)""",
    """:\d\d:\d\d\s+\d+\s(-|({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)\s+(-|({http_response_code}\d+))\s+(-|({proxy_action}\S+))\s+(-|({bytes_out}\d+))\s+(-|({bytes_in}\d+))\s+(-|unknown|({method}\S+))\s+(-|({protocol}\S+))\s+(-|({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({web_domain}[^\s]+))\s+(-|({dest_port}\d+))\s+(-|\/|({uri_path}[^\s]+))\s+(-|({uri_query}\S+))\s+(-|({user}[\w\.\-]{1,40}\$?))(\s+\S+){2}\s+((-|({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4})))(\s+(\S+|"[^"]*")){2}\s+)?(-|({mime}[^\s]+))\s+\S+\s+(-|"({user_agent}[^"]+?)\\?")\s+({action}OBSERVED)\s+"*(-|none|({categories}({category}[^",;:]{1,30})[^"]*?))\\?"*\s""",
    """({time}\d\d\d\d-\d\d-\d\d\s\d\d:\d\d:\d\d)\s\d+\s({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))\s(-|(\d{1,3}\.){3}\d{1,3}|\d+|({user}[\w\.\-]{1,40}\$?)\s).*?({action}OBSERVED)"""
    """({action}OBSERVED)\s+(?:-|\\?"(none|({categories}({category}[^\\";]+)[^"]*?))\\?")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+(\S+\s)?(?:-|({protocol}[^\s]+))\s+(?:-|({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))|({web_domain}[\w\-.]+))\s+(?:-|0|({dest_port}\d+))\s+(?:-|\/|({uri_path}[^\s]*?))\s+(?:-|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}|({uri_query}[^\s]+))\s+\S+\s+(?:-|\\*"*({user_agent}[^"]+)\\*"*)\s+[-\s]*(?:-|({=dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))?)\s+(?:-|({bytes_out}\d+)?)\s+(?:-|({bytes_in}\d+)?)""",
    """\sdst=({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?\s\w+="""
  ]


}
```