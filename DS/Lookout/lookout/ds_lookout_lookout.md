Vendor: Lookout
===============
Product: Lookout
----------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  58   |   23   |         8          |       3        |    2    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  authentication-failed<br> ↳[lookout-l-kv-endpoint-notification-success-device](Ps/pC_lookoutlkvendpointnotificationsuccessdevice.md)<br> ↳[lookout-l-cef-endpoint-notification-success-device](Ps/pC_lookoutlcefendpointnotificationsuccessdevice.md)<br>    | T1133 - External Remote Services<br>    | [<ul><li>3 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_lookout_lookout_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  network-alert<br> ↳[lookout-l-cef-alert-trigger-success-threat](Ps/pC_lookoutlcefalerttriggersuccessthreat.md)<br> ↳[lookout-l-kv-alert-trigger-success-threat](Ps/pC_lookoutlkvalerttriggersuccessthreat.md)<br><br> security-alert<br> ↳[lookout-l-cef-alert-trigger-success-threat](Ps/pC_lookoutlcefalerttriggersuccessthreat.md)<br> ↳[lookout-l-kv-alert-trigger-success-threat](Ps/pC_lookoutlkvalerttriggersuccessthreat.md)<br>    | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br> | [<ul><li>46 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_lookout_lookout_Compromised_Credentials.md)        |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  authentication-failed<br> ↳[lookout-l-kv-endpoint-notification-success-device](Ps/pC_lookoutlkvendpointnotificationsuccessdevice.md)<br> ↳[lookout-l-cef-endpoint-notification-success-device](Ps/pC_lookoutlcefendpointnotificationsuccessdevice.md)<br><br> security-alert<br> ↳[lookout-l-cef-alert-trigger-success-threat](Ps/pC_lookoutlcefalerttriggersuccessthreat.md)<br> ↳[lookout-l-kv-alert-trigger-success-threat](Ps/pC_lookoutlkvalerttriggersuccessthreat.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_lookout_lookout_Lateral_Movement.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  security-alert<br> ↳[lookout-l-cef-alert-trigger-success-threat](Ps/pC_lookoutlcefalerttriggersuccessthreat.md)<br> ↳[lookout-l-kv-alert-trigger-success-threat](Ps/pC_lookoutlkvalerttriggersuccessthreat.md)<br>    | T1068 - Exploitation for Privilege Escalation<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_lookout_lookout_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  authentication-failed<br> ↳[lookout-l-kv-endpoint-notification-success-device](Ps/pC_lookoutlkvendpointnotificationsuccessdevice.md)<br> ↳[lookout-l-cef-endpoint-notification-success-device](Ps/pC_lookoutlcefendpointnotificationsuccessdevice.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_lookout_lookout_Ransomware.md)    |
[Next Page -->>](2_ds_lookout_lookout.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution                                                                                                                                                                                    | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                               | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |