Vendor: Cisco
=============
Product: Cisco Secure Network Analytics
---------------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  86   |   41   |         15         |       2        |    2    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  netflow-connection<br> ↳[cisco-securenwanalytics-json-network-session-success-flow_id](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessflow_id.md)<br> ↳[cisco-securenwanalytics-json-network-session-success-serviceid](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessserviceid.md)<br>    | T1046 - Network Service Scanning<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_cisco_cisco_secure_network_analytics_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  dlp-alert<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-src](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccesssrc.md)<br> ↳[cisco-securenwanalytics-kv-alert-trigger-success-additionalinfo](Ps/pC_ciscosecurenwanalyticskvalerttriggersuccessadditionalinfo.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-stealthwatch](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessstealthwatch.md)<br> ↳[cisco-securenwanalytics-leef-alert-trigger-success-alarmid](Ps/pC_ciscosecurenwanalyticsleefalerttriggersuccessalarmid.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-fcdvc](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessfcdvc.md)<br> ↳[cisco-securenwanalytics-str-alert-trigger-success-z](Ps/pC_ciscosecurenwanalyticsstralerttriggersuccessz.md)<br><br> netflow-connection<br> ↳[cisco-securenwanalytics-json-network-session-success-flow_id](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessflow_id.md)<br> ↳[cisco-securenwanalytics-json-network-session-success-serviceid](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessserviceid.md)<br> | T1020 - Automated Exfiltration<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1071 - Application Layer Protocol<br>T1071.002 - Application Layer Protocol: File Transfer Protocols<br>TA0010 - TA0010<br>    | [<ul><li>30 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_cisco_cisco_secure_network_analytics_Data_Exfiltration.md)     |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  netflow-connection<br> ↳[cisco-securenwanalytics-json-network-session-success-flow_id](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessflow_id.md)<br> ↳[cisco-securenwanalytics-json-network-session-success-serviceid](Ps/pC_ciscosecurenwanalyticsjsonnetworksessionsuccessserviceid.md)<br>    | T1018 - Remote System Discovery<br>T1021 - Remote Services<br>T1021.001 - Remote Services: Remote Desktop Protocol<br>T1046 - Network Service Scanning<br>T1071 - Application Layer Protocol<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1190 - Exploit Public Fasing Application<br>T1210 - Exploitation of Remote Services<br>TA0008 - TA0008<br>TA0010 - TA0010<br>TA0011 - TA0011<br> | [<ul><li>51 Rules</li></ul><ul><li>21 Models</li></ul>](RM/r_m_cisco_cisco_secure_network_analytics_Lateral_Movement.md)      |
[Next Page -->>](2_ds_cisco_cisco_secure_network_analytics.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                         | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery                                                                                                                                                 | Lateral Movement                                                                                                                                                                                                                                          | Collection | Command and Control                                                                                                                                                                                                                                                                                                                  | Exfiltration                                                                                                                                                                                                                                                                                                                    | Impact |
| -------------------------------------------------------------------------------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           |             |                      |                 |                   | [Network Service Scanning](https://attack.mitre.org/techniques/T1046)<br><br>[Remote System Discovery](https://attack.mitre.org/techniques/T1018)<br><br> | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> |            | [Application Layer Protocol: File Transfer Protocols](https://attack.mitre.org/techniques/T1071/002)<br><br>[Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |