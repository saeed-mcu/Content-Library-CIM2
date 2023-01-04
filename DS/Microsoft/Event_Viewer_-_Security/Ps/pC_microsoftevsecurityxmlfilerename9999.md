#### Parser Content
```Java
{
Name = microsoft-evsecurity-xml-file-rename-9999
  ParserVersion = v1.0.0
  Vendor = Microsoft
  Product = Event Viewer - Security
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSS"
  Conditions = [ """<EventID>9999</EventID>""", """SubjectUserSid""" ]
  Fields = [
    """<TimeCreated SystemTime=('|")({time}\d{4}-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\d)\d+Z('|")\/>""",
    """<Computer>([^<>]+?[\\\/]+)?({host}[^<>]+)<\/Computer>""",
    """<EventID>({event_code}[^<]+)<\/EventID>""",
    """<Result>({result}[^<]+)</Result>""",
    """<Data Name =('|")SubjectIP('|").*?>({src_ip}.+?)</Data>""",
    """<Data Name =('|")SubjectUserSid('|")>({user_sid}.+?)</Data>""",
    """<Data Name =('|")SubjectDomainName('|")>({domain}.+?)</Data>""",
    """<Data Name =('|")SubjectUserName('|")>({user}.+?)</Data>""",
    """<Data Name =('|")ObjectServer('|")>({object_server}.+?)</Data>""",
# old_file_path is removed
    """<Data Name =('|")NewPath('|")>({file_path}({file_dir}.*?[\\\/]+)?({file_name}[^\\\/]+?(\.({file_ext}\w+))?))</Data>""",
  ]


}
```