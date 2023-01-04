#### Parser Content
```Java
{
Name = symantec-endpointprotection-csv-alert-trigger-success-securityriskfound
  Vendor = Symantec
  Product = Symantec Endpoint Protection
  ParserVersion = "v1.0.0"
  Conditions = [ """,セキュリティリスクが見つかりました,""", """SHA2,会社名""" ]

symantec-alert-jp = {
  Vendor = Symantec
  Product = Symantec Endpoint Protection
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d),({alert_type}[^,]+)""",
    """,IP アドレス:\s*({dest_ip}[a-fA-F\d.:]+)""",
    """,コンピュータ名:\s*({dest_host}[^,]+?)(,|\s*$)""",
    """,リスク名:\s*({alert_name}[^,]+?)(,|\s*$)""",
    """,実際の処理:\s*({action}[^,]+?)(,|\s*$)""",
    """,ユーザー:\s*({user}[^,]+?)(,|\s*$)""",
    """,カテゴリセット:\s*({category}[^,]+?)(,|\s*$)""",
    """,カテゴリの種類:\s*({threat_category}[^,]+?)(,|\s*$)""",
    """,アプリケーションハッシュ:\s*({hash_sha256}[^,]+?)(,|\s*$)""",
    """,件数:[^,]*,({file_path}({file_dir}[^,]*?[\\\/]+)?({file_name}[^\.\\\/]*?(\.({file_ext}\w+))?))\s*(,|\s*$)""",
  
}
```