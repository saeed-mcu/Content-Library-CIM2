Vendor: APC
===========
Product: APC
------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  34   |   7    |         12         |       4        |    4    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>8 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_apc_apc_Abnormal_Authentication_&_Access.md) |
|    [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)    |  failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1110 - Brute Force<br>T1110.003 - T1110.003<br>    | [<ul><li>9 Rules</li></ul>](RM/r_m_apc_apc_Brute_Force_Attack.md)    |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apc_apc_Compromised_Credentials.md)          |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_apc_apc_Data_Access.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1110 - Brute Force<br>T1110.003 - T1110.003<br>T1550.002 - Use Alternate Authentication Material: Pass the Hash<br>T1550.003 - Use Alternate Authentication Material: Pass the Ticket<br>T1558 - Steal or Forge Kerberos Tickets<br> | [<ul><li>14 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apc_apc_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  dlp-email-alert-in<br> ↳[apc-a-kv-email-receive-success-accept](Ps/pC_apcakvemailreceivesuccessaccept.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1190 - Exploit Public Fasing Application<br>T1210 - Exploitation of Remote Services<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_apc_apc_Malware.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  dlp-email-alert-in<br> ↳[apc-a-kv-email-receive-success-accept](Ps/pC_apcakvemailreceivesuccessaccept.md)<br><br> dlp-email-alert-in-failed<br> ↳[apc-a-kv-email-receive-fail-reject](Ps/pC_apcakvemailreceivefailreject.md)<br><br> failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apc_apc_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1210 - Exploitation of Remote Services<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_apc_apc_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  dlp-email-alert-in<br> ↳[apc-a-kv-email-receive-success-accept](Ps/pC_apcakvemailreceivesuccessaccept.md)<br><br> dlp-email-alert-in-failed<br> ↳[apc-a-kv-email-receive-fail-reject](Ps/pC_apcakvemailreceivefailreject.md)<br><br> failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_apc_apc_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  failed-app-login<br> ↳[apc-a-str-app-login-fail-invalidcredentials](Ps/pC_apcastrapploginfailinvalidcredentials.md)<br><br> failed-logon<br> ↳[apc-a-kv-endpoint-login-fail-smtpauthfail](Ps/pC_apcakvendpointloginfailsmtpauthfail.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_apc_apc_Ransomware.md)    |

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                           | Credential Access                                                                                                                                    | Discovery | Lateral Movement                                                                                                                                                                                                                                                                                                                                    | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Use Alternate Authentication Material: Pass the Ticket](https://attack.mitre.org/techniques/T1550/003)<br><br> | [Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br> |           | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |