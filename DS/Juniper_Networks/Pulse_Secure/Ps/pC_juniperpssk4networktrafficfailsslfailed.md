#### Parser Content
```Java
{
Name = juniper-ps-sk4-network-traffic-fail-sslfailed
  ParserVersion = "v1.0.0"
  Conditions = [ """"host":""", """"PulseSecure:"""", """SSL negotiation failed""", """Reason:""" ]
  Fields = ${JuniperParsersTemplates.cef-pulsesecure-vpn-events.Fields} [
    """SSL negotiation failed while client at source IP \'({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\' was trying to connect to \'({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\'.""",
    """Reason:\s+\'({failure_reason}[^\']+)\'"""
  ]

cef-pulsesecure-vpn-events = {
  Vendor = Juniper Networks
  Product =  Pulse Secure
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """"host":"({host}[^"]+)"""",
    """"timestamp":"({time}\d{4}-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z)""",
    """\- \[({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\]\s+(?:Default Network|Root)::(({domain}[^\\\(]+)\\)?(System|({user}[^\(]+))\(({realm}[^\)]+)?\)\[({resource}[^\]]+)?\]""",
    """\d\d\d\d\-\d\d\-\d\d \d\d:\d\d:\d\d\s+\-\s+({dest_host}[\w\-.]+)"""
  
}
```