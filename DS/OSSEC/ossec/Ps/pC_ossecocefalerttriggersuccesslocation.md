#### Parser Content
```Java
{
Name = "ossec-o-cef-alert-trigger-success-location"
Vendor = "OSSEC"
Product = "OSSEC"
TimeFormat = "yyyy-MM-dd'T'HH:mm:ssZ"
Conditions = [
  """ossec"""
  """Alert Level:"""
  """->syscheck; """
  """ Location: """
]
Fields = [
  """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d(\+|\-)\d\d:\d\d) ({host}[\w.\-]+) ossec"""
  """\sAlert Level:\s*({alert_severity}\d+)"""
  """\sRule:\s*({alert_name}[^;]+)"""
  """\sLocation:\s*\(({dest_host}[^\)]+)"""
  """Location:(\s*\([^;]*?\))?\s*(({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})|({dest_host}[^;\-]+))"""
  """\sfor:\s*'({file_path}({file_dir}[^']*?[\\\/]+)?({file_name}[^'\\\/]+?(\.({file_ext}\w+))?))'"""
  """\sCurrent SHA1:\s*'({hash_sha1}[^;']+)"""
  """\sCurrent MD5:\s*'({hash_md5}[^;']+)"""
]
ParserVersion = "v1.0.0"


}
```