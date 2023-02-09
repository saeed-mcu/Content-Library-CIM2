#### Parser Content
```Java
{
Name = symantec-bcpa-str-network-traffic-fail-tcp
  ParserVersion = v1.0.0
  Conditions = [
""" PROXIED """,
""" TCP_"""
  ]
  Fields = ${BlueCoatParserTemplates.bluecoat-proxy.Fields}[
    """(-|({failure_reason}\S+))\s+PROXIED"""
  ]
  DupFields =["http_response_code->result_code"]

bluecoat-proxy = {
  Vendor = Symantec
  Product = Symantec Web Security Service
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Fields = [
    """dvchost=(-|({host}[^\s]+))\s\w+=""",
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)\S*\s+[\w\-.]+\s+""",
    """cs6=\[([^,]+,\s){5}({src_ip}[a-fA-F\d:.]+),\s(-|({user}[^,]+))""",
    """\[[^]]+?(({action}OBSERVED|PROXIED|DENIED)),\s({categories}({category}[^,;]+)[^,]*),\s(-|({referrer}.+?))\s*,\s({http_response_code}\d+),\s(-|({proxy_action}[^,]+)),\s(unknown|({method}[^,]+)),\s(-|({mime}[^,]+)),\s({protocol}[^,]+),\s({web_domain}[^,]+),\s({dest_port}\d+),\s({uri_path}[^\n]+?)\s*,\s+(-|({uri_query}\?.*?))\s*,\s+(-|.+?),\s(none|-|({user_agent}[^\/,]+\/[\d\.]+[^\n]+?)|({=user_agent}[^,]+))?,\s(\d{1,3}\.){3}\d{1,3},\s({bytes_out}\d+),\s({bytes_in}\d+)(,\s[^,]+){5},\sclient(,\s[^,]+){22},\s(-|({dest_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({=dest_port}\d+))?)""",
    """\s({user_agent}Mozilla[^\n]+?),\s(\d{1,3}\.){3}\d{1,3},\s\d+,\s\d+""",
    """"({user_agent}Mozilla[^"]+?)\\?"\s\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3}\s\d+\s\d+"""
    """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)\s+\d+\s+(?:-|({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)\s+(\S+\s+)?(?:-|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}|\d+|TUNNELED|DENIED|FAILED|({user}[^\s\_]+))\s""",
    """\s\d+\s({src_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})\s+(-|non-interactive-user|({email_address}[^@\s]+@[^\.\s]+\.[^\s]+)|((({domain}[^\\\s]+)\\+)?({user}[^\s\\,]+)))\s+([^\s]+\s){2}({action}OBSERVED|PROXIED|DENIED)""",
    """({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\s([^\s]+\s){3}({action}OBSERVED|PROXIED|DENIED)""",
    """({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\s*$""",
    """({time}\d\d\d\d-\d\d-\d\d\s\d\d:\d\d:\d\d)\s\d+\s({src_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})\s\S+\s({proxy_action}[^\s]+)\s(\S+\s){2}(unknown|({method}[^\s]+))\s({protocol}[^\s]+)\s(({dest_ip}(\d{1,3}\.){3}\d{1,3})|({web_domain}[^\s]+))\s({url}[^\s]+)\s(\S+\s){5}({action}OBSERVED|PROXIED|DENIED)\s({category}[^\s]+)\s\S+\s({=dest_ip}[a-fA-F\d:.]+)""",
    """({action}OBSERVED|PROXIED|DENIED)\s+(?:-|"(none|({category}[^"]+))")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+((?:({dest_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?)\s+)?(?:-|({protocol}[^\s]+))\s+(?:-|({=dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})|({web_domain}[^\s]+))\s+(?:-|({=dest_port}\d+))\s+(?:-|\/|({uri_path}[^\s]+))\s+(({=dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\s+)?(?:-|({uri_query}[^\s]+))\s+\S+\s+(?:-|"({user_agent}[^"]+?)\\?")\s+(?:-|({host}[^\s]+))\s+(?:-|({bytes_out}\d+))\s+(?:-|({bytes_in}\d+))\s+("*[^"]*"*\s+){3}(?:-|({=dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}))\s+""",
    """(?:-|({host}[^\s]+))\s+(?:-|({src_port}\d+))\s+(?:-|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}|({user}[^\s]+))\s+(?:-|({bytes_in}\d+))\s+(?:-|({bytes_out}\d+))\s+(\S+\s+){3}(?:-|({http_response_code}\d+)?)\s+({action}OBSERVED|PROXIED|DENIED)\s+(?:-|"(none|({category}[^"]+))")\s+(?:-|"[^"]*")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+(?:-|"(none|({user_agent}[^"]+?))\\?")\s+(?:-|({protocol}[^\s]+))\s+(?:-|({web_domain}[^\s\.]+(\.[^\s\.]+)+)|\S+)\s+(?:-|({dest_port}\d+)|\S+)\s+(?:-|\/|({uri_path}[^\s]+))\s+(?:-|({uri_query}[^\s]+))\s+\S+\s+(?:-|({url}[^\s]+))\s""",
    """({action}OBSERVED|PROXIED|DENIED)\s+(?:-|\\?"(none|({category}[^"]+?))\\?")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+(?:-|({protocol}[^\s]+))\s+(?:-|({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})|({web_domain}[\w\-.]+))\s+(?:-|0|({dest_port}\d+))\s+(?:-|\/|({uri_path}\/[^\s]*?))\s+(?:-|({uri_query}[^\s]+))\s+\S+\s+(?:-|\\?"*({user_agent}[^"]+?)\\?"*)\s+(?:-|({host}[^\s]+))\s+(?:-|({bytes_out}\d+))\s+(?:-|({bytes_in}\d+))\s+("*[^"]*"*\s+){5}(?:-|({=dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}))\s+""",
    """\s({http_response_code}\d+)\s+({proxy_action}\S+)\s+({bytes_out}\d+)\s+({bytes_in}\d+)\s+(unknown|({method}\S+))\s+({protocol}\S+)\s+({web_domain}\S+)\s+(-|({url}(({=protocol}[^:\\\/\s,"]+):[\\\/]+)?[\\\/]*(({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})|({=web_domain}[^\\\/\s:,"]+))(:({dest_port}\d+))?(\/|({uri_path}\/[^\s\?",]*))?({uri_query}\?[^"\s]*)?))\s+(-|({user}[^\s]+))\s+\S+\s+(({=dest_ip}[A-Fa-f:\d.]+)|({=web_domain}[\w\-.]+))\s+(-|({mime}\S+))\s+"({user_agent}[^"]+?)\\?"\s+({action}OBSERVED|PROXIED|DENIED)""",
    """:\d\d:\d\d\s+\d+\s(-|({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)\s+(-|({http_response_code}\d+))\s+(-|({proxy_action}\S+))\s+(-|({bytes_out}\d+))\s+(-|({bytes_in}\d+))\s+(-|unknown|({method}\S+))\s+(-|({protocol}\S+))\s+(-|({dest_ip}(\d{1,3}\.){3}\d{1,3})|({web_domain}[^\s]+))\s+(-|({dest_port}\d+))\s+(-|\/|({uri_path}[^\s]+))\s+(-|({uri_query}\S+))\s+(-|({user}\S+))(\s+\S+){2}\s+((-|({=dest_ip}[\da-fA-F.:]+))(\s+(\S+|"[^"]*")){2}\s+)?(-|({mime}[^\s]+))\s+\S+\s+(-|"({user_agent}[^"]+?)\\?")\s+({action}OBSERVED|PROXIED|DENIED)\s+"*(-|none|({categories}({category}[^",;:]{1,30})[^"]*?))\\?"*\s""",
    """({time}\d\d\d\d-\d\d-\d\d\s\d\d:\d\d:\d\d)\s\d+\s({src_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})\s(-|(\d{1,3}\.){3}\d{1,3}|({user}[^\s]+)\s).*?\s.*?({action}OBSERVED|PROXIED|DENIED)\s+(?:-|\\?"(none|({categories}({category}[^\\";]+)[^"]*?))\\?")\s+(?:-|({referrer}[^\s]+))\s+(?:-|({http_response_code}\d+)?)\s+(?:-|({proxy_action}[^\s]+))\s+(?:-|unknown|({method}[^\s]+))\s+(?:-|({mime}[^\s]+))\s+(\S+\s)?(?:-|({protocol}[^\s]+))\s+(?:-|({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})|({web_domain}[\w\-.]+))\s+(?:-|0|({dest_port}\d+))\s+(?:-|\/|({uri_path}[^\s]*?))\s+(?:-|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}|({uri_query}[^\s]+))\s+\S+\s+(?:-|\\*"*({user_agent}[^"]+)\\*"*)\s+[-\s]*(?:-|({=dest_ip}[A-Fa-f\d\.:]+)?)\s+(?:-|({bytes_out}\d+)?)\s+(?:-|({bytes_in}\d+)?)"""
  
}
```