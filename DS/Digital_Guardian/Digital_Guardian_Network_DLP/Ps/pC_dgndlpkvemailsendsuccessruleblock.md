#### Parser Content
```Java
{
Name = dg-ndlp-kv-email-send-success-ruleblock
  ParserVersion = v1.0.0
  Conditions = [ """Rule_Violation="True"""", """Block_Code="Rule Block"""" ]
  Fields = ${DGParsersTemplates.splunk-digitalguardian-dlp-alert.Fields}[
    """[^_]Custom_String_4="({alert_name}[^"]+)""",
    """[^_]Block_Code="({alert_type}[^"]+)""",
    """[^_]Bytes_Read="(?:|({bytes}\d+))"""",
  ]

splunk-digitalguardian-dlp-alert = {
  Vendor = Digital Guardian
  Product = Digital Guardian Network DLP
  TimeFormat = "MM/dd/yyyy HH:mm:ss a"
  Fields = [
    """[^_](Agent_UTC_Time|Server_UTC_Timestamp)="({time}\d+\/\d+\/\d\d\d\d \d+:\d+:\d+ (am|AM|pm|PM))"""",
    """[^_]Computer_Name ="([^\/\\"]+[\/\\]+)?({host}[^"]+)"""",
    """[^_]User_Name ="(?:|(({domain}[^"\/\\]+)[\/\\]+)?({user}[^"]+))"""",
    """[^_]Domain_Name ="(?:|({domain}[^"]+))"""",
    """[^_]Rule="({alert_name}[^"]+)""",
    """[^_]Operation="({alert_type}[^"]+)""",
    """[^_]Protocol="({protocol}[^"]+)""",
    """[^_]Severity="({alert_severity}[^"]+)"""",
    """[^_]Destination_Device_ID="({device_id}[^"]+)"""",
    """[^_]Source_File="(?:|({file_name}[^"]+))"""",
    """[^_]Destination_File="(?:|({file_name}[^"]+))"""",
    """[^_]Bytes_Written="(?:|({bytes}\d+))"""",
    """[^_]IP_Address="(?:|({dest_ip}[^"]+))"""",
    """[^_]Application="(?:|({process_name}[^"]+))"""",
    """[^_]Email_Recipient="(?:|({target}[^"]+))"""",
    """[^_]Computer_Type="(?:|({os}[^"]+))""""
  ]
  DupFields = [ "host->src_host" ]
  SOAR {
    IncidentType = "dlp"
    DupFields = ["time->startedDate", "vendor->source", "rawLog->sourceInfo", "user->dlpUser", "alert_name->dlpPolicy", "protocol->dlpProtocol", "src_host->dlpDeviceName", "file_name->dlpFileName", "bytes->dlpFileSize"]
    NameTemplate = """Digital Guardian DLP Alert ${alert_name} found"""
    ProjectName = "SOC"
    EntityFields = [
      {EntityType="device", Name ="src_address", Fields=["src_host->host_name"]},
      {EntityType="device", Name ="dest_address", Fields=["dest_ip->ip_address"]},
      {EntityType="user", Name ="windows_id", Fields=["user->windows_id"]}
    ]
    }
  },

  leef-digitalguardian-dlp-email-alert-out = {
  Vendor = Digital Guardian
  Product = Digital Guardian Endpoint Protection
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Fields = [
    """devTime=({time}\w+ \d\d \d\d\d\d \d\d:\d\d:\d\d)""",
    """({host}[\w\-.]+) LEEF:""",
    """accountName =(({email_domain}[^\\]+)\\+)?({user}[^\\\s]+?)\s*(\w+=|$)""",
    """IdentHostName =(({email_domain}[^\\])+\\+)?({dest_host}[\w\-.]+?)\s*(\w+=|$)""",
    """src=({src_ip}[A-Fa-f:\d.]+)""",
    """dst=({dest_ip}[A-Fa-f:\d.]+)""",
    """EmailSender=({email_address}.+?)\s*(\w+=|$)""",
    """usrName =(?![^\s]+@[^\s]+)(({email_domain}[^\\]+)\\+)?({user}[^\\\s@]+)\s*(\w+=|$)""",
    """usrName =(?=[^\s]+@[^\s]+)({email_address}[^\s@]+@[^\s]+)""",
    """EmailRecipient=(|({dest_email_address}[^\s,;]+))""",
    """EmailRecipient=(|({email_recipients}.+?))\s*(\w+=|$)""",
    """EmailRecipient=({external_address}[^@]+@[^@\s,;]+).*?\s*(\w+=|$)""",
    """EmailSubject=(|({email_subject}.+?))\s*(\w+=|$)""",
    """sev=({alert_severity}\d+)""",
    """srcBytes=({bytes}\d+)""",
    """FileSizeMB=({bytes}\d+)""",
    """FileSize({bytes_unit}MB)""",
    """DestinationFile=(|({email_attachments}[^\.]+\.({file_ext}.+?)))\s*(\w+=|$)""",
  
}
```