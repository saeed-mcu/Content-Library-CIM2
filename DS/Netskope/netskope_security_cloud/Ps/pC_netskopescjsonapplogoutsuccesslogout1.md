#### Parser Content
```Java
{
Name = netskope-sc-json-app-logout-success-logout-1
  ParserVersion = v1.0.0
  Product = Netskope Security Cloud
  Conditions = [ """"audit_log_event":"Logout Successful"""" , """"type":"""" ,""""sAMAccountName":""""]

json-netskope-activity = {
  Vendor = Netskope
  Product = Netskope Security Cloud
  TimeFormat = "epoch_sec"
  
  Fields = [
    """"timestamp":({time}\d{10})""",
	""""user":"(({email_address}([A-Za-z0-9]+[!#$%&'+-\/=?^_`~])*[A-Za-z0-9]+@[^\]\s"\\,\|]+\.[^\]\s"\\,\|]+)|({user}[^"]+))""",
	""""data_values":\[?"({additional_info}[^\]"]+)""",
  
}
```