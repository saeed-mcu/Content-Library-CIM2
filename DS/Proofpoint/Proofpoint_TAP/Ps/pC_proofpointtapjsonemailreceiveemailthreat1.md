#### Parser Content
```Java
{
Name = proofpoint-tap-json-email-receive-emailthreat-1
Conditions = [
  """Proofpoint"""
  """"threatsInfoMap\":"""
  """"threatTime\":"""
  """"threat\":"""
  """"default_inbound\""""
]
ParserVersion = "v1.0.0"

s-proofpoint-email-in-1 = {
  Vendor = Proofpoint
  Product = Proofpoint TAP
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """threatTime":\s*"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)""",
    """messageTime":\s*"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)""",
    """spamScore":\s*({spam_score}\d+)""",
    """phishScore":\s*({phishing_score}\d+)""",
    """(,|")malwareScore":\s*({malware_score}\d+)""",
    """messageSize":\s*({bytes}\d+)""",
    """classification":\s*"({alert_type}[^",]+?)\s*(,|")""",
    """"threatsInfoMap":\s*\[\{"[^}\]]+?"classification":\s*"({alert_type}[^"]+)""",
    """"threatsInfoMap":\s*\[\{"[^}\]]+?"threatType":\s*"({alert_type}[^"]+)""",
    """subject":\s*"\s*(\{\\|({email_subject}[^",]+?))\s*(,|")""",
    """suser=({email_address}[^"\s,@]+@[^"\s,@]+)""",
    """duser=({dest_email_address}[^"\s,@]+@[^"\s,@]+)""",
    """sender":\s*"({email_address}[^"\s,@]+@[^"\s,@]+)""",
    """recipient":\s*\[?"({email_recipients}[^",;]+@[^",;]+[^"]*)""",
    """recipient":\s*\[?"({dest_email_address}[^",;]+@[^",;]+)""",
    """GUID":\s*"({alert_id}[^",]+?)\s*(,|")""",
    """senderIP":\s*"({src_ip}[a-fA-F\d.:]+)""",
    """url":\s*"({malware_url}[^",]+?)\s*(,|")""",
    """\scs1=Policy \[id: [^\]]*? ; name: ({alert_name}[^\]]+?) ; category: ({category}[^\]]+?)]""",
    """threat":\s*"\s*({malware_url}[^",]+?)\s*(,|")""",
    """,\s*"filename":\s*"(?!text(\.txt|\.html|-calendar))\s*({email_attachments}({email_attachment}[^",;]+)[^"]*?)",\s*"\w+":""",
    ""","fromArray":"({action}[^\]]+?)","\w+":""",
    """eventType":\s*"({action}[^",]+?)\s*(,|")""",
    """"messageID":\s*"<?({message_id}[^>"]+)""",
    """src-account-name":"({account_name}[^"]+)"""
  ]
  DupFields = [ "email_attachment->file_name" 
}
```