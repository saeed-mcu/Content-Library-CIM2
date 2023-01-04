#### Parser Content
```Java
{
Name = trendmicro-t-cef-database-login-fail-loginfailed
Vendor = Trend Micro
Product = Trend Micro
TimeFormat = "yyyy-MM-dd HH:mm:ss.SSSSSSZ"
Conditions = [
  """CEF:"""
  """|Database Server - Microsoft SQL|"""
  """Login failed"""
]
Fields = [
  """\Wdvc=(|({host}.+?))(\s+\w+=|\s*$|\s*")"""
  """\Wshost=(|({src_host}.+?))(\s+\w+=|\s*$|\s*")"""
  """Login failed for user\s*'(({domain}[^']+?)\\+)?({user}[^'\\]+)'"""
  """Reason:\s*({failure_reason}.+?)\s*\."""
]
ParserVersion = "v1.0.0"


}
```