Vendor: Cisco
=============
Product: Secure Network Analytics
---------------------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  32   |   12   |     6      |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  security-alert<br> ↳[cisco-securenwanalytics-kv-alert-trigger-success-additionalinfo](Ps/pC_ciscosecurenwanalyticskvalerttriggersuccessadditionalinfo.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-stealthwatch](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessstealthwatch.md)<br> ↳[cisco-securenwanalytics-leef-alert-trigger-success-alarmid](Ps/pC_ciscosecurenwanalyticsleefalerttriggersuccessalarmid.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-fcdvc](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessfcdvc.md)<br> ↳[cisco-securenwanalytics-str-alert-trigger-success-z](Ps/pC_ciscosecurenwanalyticsstralerttriggersuccessz.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br> | [<ul><li>25 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_cisco_secure_network_analytics_Compromised_Credentials.md) |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  security-alert<br> ↳[cisco-securenwanalytics-kv-alert-trigger-success-additionalinfo](Ps/pC_ciscosecurenwanalyticskvalerttriggersuccessadditionalinfo.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-stealthwatch](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessstealthwatch.md)<br> ↳[cisco-securenwanalytics-leef-alert-trigger-success-alarmid](Ps/pC_ciscosecurenwanalyticsleefalerttriggersuccessalarmid.md)<br> ↳[cisco-securenwanalytics-cef-alert-trigger-success-fcdvc](Ps/pC_ciscosecurenwanalyticscefalerttriggersuccessfcdvc.md)<br> ↳[cisco-securenwanalytics-str-alert-trigger-success-z](Ps/pC_ciscosecurenwanalyticsstralerttriggersuccessz.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_cisco_secure_network_analytics_Lateral_Movement.md)    |
[Next Page -->>](2_ds_cisco_secure_network_analytics.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                               | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           |                  |            |                     |              |        |