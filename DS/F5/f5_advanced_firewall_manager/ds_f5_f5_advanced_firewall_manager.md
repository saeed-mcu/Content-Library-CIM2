Vendor: F5
==========
Product: F5 Advanced Firewall Manager
-------------------------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  72   |   37   |     7      |       2        |    2    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md) |  dlp-alert<br> ↳[f5-afm-cef-alert-trigger-attack](Ps/pC_f5afmcefalerttriggerattack.md)<br><br> network-connection-successful<br> ↳[f5-afm-kv-network-traffic-success-networktraffic](Ps/pC_f5afmkvnetworktrafficsuccessnetworktraffic.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br>    | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_f5_f5_advanced_firewall_manager_Data_Exfiltration.md) |
|         [Data Leak](../../../UseCases/uc_data_leak.md)         |  dlp-alert<br> ↳[f5-afm-cef-alert-trigger-attack](Ps/pC_f5afmcefalerttriggerattack.md)<br><br> network-connection-successful<br> ↳[f5-afm-kv-network-traffic-success-networktraffic](Ps/pC_f5afmkvnetworktrafficsuccessnetworktraffic.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br>    | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_f5_f5_advanced_firewall_manager_Data_Leak.md)         |
|  [Lateral Movement](../../../UseCases/uc_lateral_movement.md)  |  dlp-alert<br> ↳[f5-afm-cef-alert-trigger-attack](Ps/pC_f5afmcefalerttriggerattack.md)<br><br> network-connection-successful<br> ↳[f5-afm-kv-network-traffic-success-networktraffic](Ps/pC_f5afmkvnetworktrafficsuccessnetworktraffic.md)<br> | T1071 - Application Layer Protocol<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1190 - Exploit Public Fasing Application<br>TA0010 - TA0010<br>TA0011 - TA0011<br> | [<ul><li>39 Rules</li></ul><ul><li>17 Models</li></ul>](RM/r_m_f5_f5_advanced_firewall_manager_Lateral_Movement.md)  |
|    [Malware](../../../UseCases/uc_malware.md)    |  dlp-alert<br> ↳[f5-afm-cef-alert-trigger-attack](Ps/pC_f5afmcefalerttriggerattack.md)<br><br> network-connection-successful<br> ↳[f5-afm-kv-network-traffic-success-networktraffic](Ps/pC_f5afmkvnetworktrafficsuccessnetworktraffic.md)<br> | TA0002 - TA0002<br>TA0011 - TA0011<br>    | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_f5_f5_advanced_firewall_manager_Malware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                         | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                                                                                                      | Exfiltration                                                                | Impact |
| -------------------------------------------------------------------------------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------- | ------ |
| [Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           |             |                      |                 |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |