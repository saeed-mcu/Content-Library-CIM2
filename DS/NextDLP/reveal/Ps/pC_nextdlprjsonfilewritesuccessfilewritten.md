#### Parser Content
```Java
{
Name = nextdlp-r-json-file-write-success-filewritten
  Vendor = NextDLP
  Conditions = [ """reveal""", """file written to USB storage device""", """"tags":""", """"sensor_type": "AGENT_POLICY"""", """name":""", """datatracking""" ]
  Fields = ${QUSHRevealParserTemplates.json-qush-reveal.Fields} [
    """({operation}file written)"""
    """"usb_vid":\s*\["({device_id}[^"]+)"""
  ]
  ParserVersion = v1.0.0

json-qush-reveal = {
    Product = Reveal
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
    Fields = [
      """"timestamp"+:\s*"+({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)"""
      """"host":\s*\["({dest_host}[\w\-\.]+)"""
      """"agent_hostname":\s*"({host}[\w\-\.]+)""""
      """"description"+:\s*"+({additional_info}[^\n]+?)\s*","""
      """"username"+:\s*"+(({full_name}[^\\\s"]+\s[^"\\]+)|(({domain}[^"\s\\]+)\\+)?({user}[\w\.\-]{1,40}\$?))","""
      """"user_name":\s*"(({full_name}({first_name}[^\s"]+)\s({last_name}[^\s"]+))|({user}[\w\.\-]{1,40}\$?))"""
      """"account_name"+:\s*\["+([^,\]]+,\s*")?((({domain}[^\\",]+)\\+)?({user}[\w\.\-]{1,40}\$?))"\]"""
      """"user_email":\s*"({email_address}([A-Za-z0-9]+[!#$%&'+-\/=?^_`~])*[A-Za-z0-9]+@[^\]\s"\\,\|]+\.[^\]\s"\\,\|]+)""""
      """"binary_path"+:\s*"+[\\]*({process_path}({process_dir}[^"]+?)\\+({process_name}[^"\\]+))""""
      """"file_name":\s*\["({file_path}({file_dir}\w:([^"]+)?[\\\/]))?({file_name}[^"\\\/]+?(\.(\.\.|({file_ext}[^"\\\/\.]+))))""""
      """"file_path":\s*\["[\\]*({file_path}[^"]+)""""
      """"created_by":"policy:[^"]+?name=({event_name}[^"]+)""""
      """"tags":\s*\[[^\]]*?"({tag}[^"\]]+)"\]"""
      """"name":\s*"\s*({event_name}[^"]+?)\s*""""
      """"application_name":\s*\["({app}[^"]+)""""
      """"destination_ip":\s*\["({dest_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))"\]""",
      """"destination_port":\s*\["({dest_port}\d{1,5})"\]""",
      """"source_ip":\s*\["({src_ip}((([0-9a-fA-F.]{0,4}):{1,2}){1,7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))"\]""",
      """"source_port":\s*\["({src_port}\d{1,5})"\]"""
      """"url":\s*\["({url}[^"\]]+)"(,|\])"""
   
}
```