#### Parser Content
```Java
{
Name = cyberark-pam-kv-app-activity-success-otherinfo
    Vendor = CyberArk
    Product = "CyberArk Privilege Access Manager"
    TimeFormat = ["yyyy-MM-dd HH:mm:ss", "MMM dd HH:mm:ss"]
    Conditions = [ """Operation:""", """ObjectType:""", """OtherInfo:""" ]
    Fields = [
                """Operation: ({operation}.*?) ObjectType""",
                """:\d\d\s({host}[^=]+)\sPAR""",
                """({time}\w+ \d+ \d+:\d+:\d+)?\s({host}[^=\[:]+)\sPAR""",
                """(AdminName|UserName): ({user}[\w\.\-\!\#\^\~]{1,40}\$?)\sOperation""",
                """Failed\?\s({event_subtype}\d)\s""",
                """Target: ({app}[^\s].+)\sRole""",
                """OtherInfo:\s({additional_info}.+)\s""",
                """Role:\s({app_group}.+?)\s"""
    ]
	ParserVersion = "v1.0.0"


}
```