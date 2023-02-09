Vendor: Barracuda
=================
Product: Barracuda Email Security Gateway
-----------------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  96   |   43   |         7          |       5        |    5    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>12 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Account_Manipulation.md)    |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>39 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Compromised_Credentials.md)         |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br><br> dlp-email-alert-out<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br><br> dlp-email-alert-out-failed<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1114.003 - Email Collection: Email Forwarding Rule<br> | [<ul><li>37 Rules</li></ul><ul><li>16 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Data_Leak.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br><br> dlp-email-alert-in<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br> ↳[barracuda-esg-cef-email-receive-barracudanetworks](Ps/pC_barracudaesgcefemailreceivebarracudanetworks.md)<br><br> dlp-email-alert-out<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br> | T1078 - Valid Accounts<br>T1190 - Exploit Public Fasing Application<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  dlp-email-alert-out<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Phishing.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Privilege_Escalation.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[barracuda-esg-cef-app-activity-success-scan](Ps/pC_barracudaesgcefappactivitysuccessscan.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Ransomware.md)    |
|    [Workforce Protection](../../../UseCases/uc_workforce_protection.md)    |  dlp-email-alert-out<br> ↳[barracuda-esg-str-email-send-receive-scan](Ps/pC_barracudaesgstremailsendreceivescan.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_barracuda_barracuda_email_security_gateway_Workforce_Protection.md)    |
[Next Page -->>](2_ds_barracuda_barracuda_email_security_gateway.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration                                                                                                                                                                                                                                         | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br> |        |