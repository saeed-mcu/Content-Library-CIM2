#### Parser Content
```Java
{
Name = dell-sw-kv-vpn-logout-success-infosystem
  Vendor = Dell
  Product = SonicWALL
  TimeFormat = "dd/MMM/yyyy:HH:mm:ss"
  Conditions = [ """Info System Session End:""",]
  Fields = [
    """:\s.+?\]\s+({host}[^\s]+).+?\sEnd:.+?\(({user}[^\)]+)"""
  ]
  ParserVersion = "v1.0.0"


}
```