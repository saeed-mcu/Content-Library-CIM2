#### Parser Content
```Java
{
Name = accellion-kw-kv-app-activity-success-userdeleted
Product = Kiteworks
Conditions = [
  """User deleted"""
  """Activity:"""
]
ParserVersion = "v1.0.0"

q-kiteworks-file-activity.Fields}[
   """({access}Downloaded) file ({src_file_path}({file_dir}.*?[\\\/]+)?({src_file_name}[^\\\/]+?(\.({src_file_ext}[^\.]+))?))\.\s+File:\s"""
  ]
  DupFields = [ "src_file_name->file_name" 
}
```