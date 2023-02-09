#### Parser Content
```Java
{
Name = sentinelone-singularityp-cef-file-write-success-deep
  ParserVersion = v1.0.0
  TimeFormat = "epoch"
  Conditions = [
    """"SentinelOne""""
    """Deep Visibility Endpoint"""
    """fileCreation {"""
  ]
  Fields = ${SentinelOneParsersTemplates.sentinelone-activity.Fields} [
    """\smillisecondsSinceEpoch:\s*({time}\d{13})""",
    """type"+:"+file"+,"+name"+:"+({file_path}({file_dir}[^"]+?)[\\\/]*({file_name}[^\\\/"]+?(\.({file_ext}[^\.\s"\\\/]+))?))"""",
    """({event_name}fileCreation)""",
  ]
  DupFields = ["host->dest_host"]

sentinelone-activity {
    Vendor = SentinelOne
    Product = Singularity Platform
    TimeFormat = "epoch"
    Fields = [
      """\smillisecondsSinceEpoch:\s*({time}\d{13})""",
      """\\ncomputer_name:\s*"+({host}[^"]+)""",
      """\\nos_name:\s*"+({os}[^"]+)""",
      """\\nagent_version:\s*"+({user_agent}[^"]+)""",
      """\ssizeBytes:\s*({bytes}\d+)""",
      """user\s*\{[^\}]+?sid:[^"]*?"+({user_sid}[^"\\]+)""",
      """user\s*\{\\n\s+name:\s+[\\\/]?"*((NT AUTHORITY|({domain}[^\\"]+))[\\\/]+)?(SYSTEM|NETWORK SERVICE|LOCAL SERVICE|({user}[^\\"]+))""",
      """"app-username":"((NT AUTHORITY|({domain}[^\\"]+))[\\\/]+)?(SYSTEM|NETWORK SERVICE|LOCAL SERVICE|({user}[^"]+?))\s*"""",
      """\ssha256:\s*[\\\/]?"+({hash_sha256}[^"\\]+)""",
      """\smd5:\s*[\\\/]?"+({hash_md5}[^"\\]+)""",
      """\spid:\s*({process_id}\d+)""",
      """path:\s+[\\\/]?"+({process_path}({process_dir}[^"]+?)[\\\/]*({process_name}[^"\\\/]+))[\\\/]*"""",
      """destinationAddress\s.*?address:\s*[\\\/]?"+({dest_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({dest_port}\d+))?""",
      """destinationAddress\s.*?port:\s*({dest_port}\d+)""",
      """\sstatus:\s*({result}\w+)""",
      """sourceAddress\s.*?port:\s*({src_port}\d+)""",
      """sourceAddress\s.*?address:\s*[\\\/]?"+({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?""",
      """sha1:\s*"*({hash_sha1}[^"]+)""""
    
}
```