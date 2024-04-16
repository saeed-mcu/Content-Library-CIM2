#### Parser Content
```Java
{
Name = "microsoft-evsecurity-kv-share-access-5145-7"
Vendor = "Microsoft"
Product = "Event Viewer - Security"
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Conditions = [
"""A network share object was checked to see whether client can be granted desired access"""
"""Account Name:"""
"""EventTime"""
]
Fields = [
"""({event_name}A network share object was checked to see whether client can be granted desired access)"""
"""({event_code}5145)"""
"""({host}[\w\-.]+)\s+(?i)((audit|success)( |_)(success|audit))"""
"""\"EventTime\":\"({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)"""
"""Logon ID:\s*((\\)[rnt])*({login_id}\S+?)((\\)[rnt])*\s*Network Information:"""
"""Account Name:\s*((\\)[rnt])*({user}[\w\.\-]{1,40}\$?)((\\)[rnt])*\s*Account Domain:"""
"""Account Domain:\s*((\\)[rnt])*({domain}\S+?)((\\)[rnt])*\s*Logon ID:"""
"""Object Type:\s*((\\)[rnt])*({file_type}.+?)((\\)[rnt])*\s*Source Address:"""
"""Source Address:\s*((\\)[rnt])*(::1|({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?)((\\)[rnt])*\s*Source Port:"""
"""Share Name:\s*((\\)[rnt])*(?:\\\\\*\\)?({share_name}.+?)((\\)[rnt])*\s*Share Path:"""
"""Share Path:\s*((\\)[rnt])*(?:[\\\?]+)?(?:\s*|({share_path}(({d_parent}.+?)\\)?(|({d_name}[^\\]*?)))\\?)((\\)[rnt])*\s*Relative Target Name:"""
"""Relative Target Name:\s*((\\)[rnt])*\\?(?:\s*|(?:({file_dir}.+?)\\)?(|({file_name}[^\\:\/]+?(?:\.({file_ext}[^\.]+?))?))(?:\\HEAD|:.+?|\\|\s|((\\)[rnt])*)\s*)Access Request Information:"""
"""Accesses:.*({access}SYNCHRONIZE|Execute|Traverse|Read|READ|WRITE_DAC|WRITE_OWNER|WriteAttributes|WriteEA|WriteData|AppendData|delete|Delete).*Access Check Results:"""
"""Access Check Results:\s*({result}-)\s"""
"""Access Check Results:.*({result}Granted|Denied)\s+by"""
"""Source Port(=|:)\s*({src_port}\d+)"""
]
DupFields = [
"host->dest_host"
]
ParserVersion = "v1.0.0"


}
```