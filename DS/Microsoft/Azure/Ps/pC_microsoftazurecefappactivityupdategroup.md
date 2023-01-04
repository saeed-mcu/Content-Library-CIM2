#### Parser Content
```Java
{
Name = microsoft-azure-cef-app-activity-updategroup
  Conditions = [ """CEF:""", """|Azure""", """|Update group|""" ]
  ParserVersion = "v1.0.0"

cef-azure-app-activity-1 = {
Vendor = Microsoft
Product = Azure
TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
Fields = [
"""\Wdvc=(Unknown|Personal|({host}\S+))"""
"""\Wdvchost=(?:Unknown|Personal|({host}[\w\-.]+))\s+\w+="""
"""act=({operation}[^\s]+)\s+(\w+=|$)"""
"""\Wrt=({time}\d+)"""
"""({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z) \S+ """
"""\Wduser=(anonymous|Unknown|email|({email_address}[^@=]+@({email_domain}[^@=]+?))|({user}[^=]+?))(\s+\w+=|\s*$)"""
"""\Wsuser=(anonymous|Unknown|email|({email_address}[^@=]+@({email_domain}[^@=]+?))|({user}[^=]+?))(\s+\w+=|\s*$)"""
"""\Woutcome=({result}[^\s]+)\s+(\w+=|$)"""
"""CEF:([^\|]*\|){2}({app}[^\|]+)"""
"""destinationServiceName =({app}[^=]+?)\s+(\w+=|$)"""
"""src=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""
"""\"description\":\"({additional_info}[^\"]+?)\s*\""""
"""\"SourceAccountDisplayName\",\"value\":\"({full_name}({first_name}[^\s\"]+)\s({last_name}[^\s\"]+))\""""
"""\"SourceAccountUpnName\",\"value\":\"({email_address}[^@\"]+@({email_domain}[^\"]+))\""""
"""\"SourceComputerDnsName\",\"value\":\"({src_host}[^\"]+)\""""
"""\"DestinationComputerDnsName\",\"value\":\"({dest_host}[^\"]+)\""""
"""\"DestinationIpAddress\",\"value\":\"({dest_ip}[a-fA-F\d.:]+)\""""
"""\"Protocol\",\"value\":\"({protocol}[^\"]+)\""""

}
```