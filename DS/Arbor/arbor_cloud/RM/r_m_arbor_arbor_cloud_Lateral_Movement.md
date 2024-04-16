Rules by Product and UseCase
============================
Vendor: Arbor
-------------
### Product: [Arbor Cloud](../ds_arbor_arbor_cloud.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  25   |   10   |         5          |       1        |    0    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| network-connection-failed | <b>T1190 - Exploit Public Fasing Application</b><br> ↳ <b>A-NETF-Log4j-IP</b>: There was a failed attempt to access this asset by an external IP associated with Log4j exploit<br><br><b>TA0010 - TA0010</b><br> ↳ <b>A-NETF-HCountry-Outbound-F</b>: First failed outbound connection to this country from asset<br> ↳ <b>A-NETF-HCountry-Outbound-A</b>: Outbound connection to abnormal country for asset has failed<br> ↳ <b>A-NETF-OCountry-Outbound-F</b>: First failed outbound connection to this country from organization<br> ↳ <b>A-NETF-OCountry-Outbound-A</b>: Outbound connection to abnormal country for the organization has failed<br> ↳ <b>A-NETF-ZCountry-Outbound-A</b>: Outbound connection to abnormal country for the zone has failed<br> ↳ <b>A-NETF-ZCountry-Outbound-F</b>: First failed outbound connection to this country from zone<br> ↳ <b>A-NETF-OdPort-Outbound-F</b>: First outbound traffic to previously unused port for the organization failed<br> ↳ <b>A-NETF-OdPort-Outbound-A</b>: Outbound traffic to abnormal port for the organization failed<br> ↳ <b>A-NETF-OsH-Outbound-F</b>: First failed outbound connection for host in the organization<br> ↳ <b>A-NETF-OsH-Outbound-A</b>: Abnormal outbound connection from host failed in the organization<br> ↳ <b>A-NETF-ZsH-Outbound-F</b>: First failed outbound connection for host in the zone<br> ↳ <b>A-NETF-ZsH-Outbound-A</b>: Abnormal outbound connection from host failed in the zone<br> ↳ <b>A-NETF-HsH-Outbound-F</b>: First failed outbound connection for host<br> ↳ <b>A-NETF-HsH-Outbound-A</b>: Abnormal outbound connection from host failed<br> ↳ <b>A-NETF-OsZ-Outbound-F</b>: First failed outbound connection from zone<br> ↳ <b>A-NETF-OsZ-Outbound-A</b>: Abnormal outbound connection from zone failed<br><br><b>TA0011 - TA0011</b><br> ↳ <b>A-NETF-HdPort-Outbound-F</b>: First failed outbound connection on port for asset<br> ↳ <b>A-NETF-HdPort-Outbound-A</b>: Outbound connection to abnormal port for asset has failed<br> ↳ <b>A-NETF-ZdPort-Outbound-F</b>: First outbound connection on port has failed for zone<br> ↳ <b>A-NETF-ZdPort-Outbound-A</b>: Abnormal outbound connection on port has failed for zone<br> ↳ <b>A-NETF-HCountry-Outbound-F</b>: First failed outbound connection to this country from asset<br> ↳ <b>A-NETF-HCountry-Outbound-A</b>: Outbound connection to abnormal country for asset has failed<br> ↳ <b>A-NETF-OCountry-Outbound-F</b>: First failed outbound connection to this country from organization<br> ↳ <b>A-NETF-OCountry-Outbound-A</b>: Outbound connection to abnormal country for the organization has failed<br> ↳ <b>A-NETF-ZCountry-Outbound-A</b>: Outbound connection to abnormal country for the zone has failed<br> ↳ <b>A-NETF-ZCountry-Outbound-F</b>: First failed outbound connection to this country from zone<br> ↳ <b>A-NETF-TI-IP-Outbound</b>: Outbound failed connection to a known malicious IP<br> ↳ <b>A-NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>A-NETF-TI-H-Outbound</b>: Outbound failed connection to a known malicious host<br> ↳ <b>A-NETF-OdPort-Outbound-F</b>: First outbound traffic to previously unused port for the organization failed<br> ↳ <b>A-NETF-OdPort-Outbound-A</b>: Outbound traffic to abnormal port for the organization failed<br> ↳ <b>A-NETF-OsH-Outbound-F</b>: First failed outbound connection for host in the organization<br> ↳ <b>A-NETF-OsH-Outbound-A</b>: Abnormal outbound connection from host failed in the organization<br> ↳ <b>A-NETF-ZsH-Outbound-F</b>: First failed outbound connection for host in the zone<br> ↳ <b>A-NETF-ZsH-Outbound-A</b>: Abnormal outbound connection from host failed in the zone<br> ↳ <b>A-NETF-HsH-Outbound-F</b>: First failed outbound connection for host<br> ↳ <b>A-NETF-HsH-Outbound-A</b>: Abnormal outbound connection from host failed<br> ↳ <b>A-NETF-OsZ-Outbound-F</b>: First failed outbound connection from zone<br> ↳ <b>A-NETF-OsZ-Outbound-A</b>: Abnormal outbound connection from zone failed<br><br><b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>A-NETF-TOR-Outbound</b>: Outbound failed connection to a known TOR IP<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>A-NETF-ZdPort-Outbound-F</b>: First outbound connection on port has failed for zone |  • <b>A-NET-OsZ-Outbound</b>: Outbound communicating zones in the organization<br> • <b>A-NET-HsH-Outbound</b>: Outbound communicating hosts for the asset<br> • <b>A-NET-ZsH-Outbound</b>: Outbound communicating hosts in the zone<br> • <b>A-NET-OsH-Outbound</b>: Outbound communicating hosts<br> • <b>A-NET-OdPort-Outbound</b>: Outbound destination ports per organization<br> • <b>A-NETF-ZCountry-Outbound</b>: Failed outbound country per zone<br> • <b>A-NETF-OCountry-Outbound</b>: Failed outbound country per organization<br> • <b>A-NETF-HCountry-Outbound</b>: Failed outbound country per asset<br> • <b>A-NET-ZdPort-Outbound</b>: Outbound destination ports per zone<br> • <b>A-NET-HdPort-Outbound</b>: Outbound destination ports per asset |