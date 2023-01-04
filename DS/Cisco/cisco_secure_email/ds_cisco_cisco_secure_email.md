Vendor: Cisco
=============
Product: Cisco Secure Email
---------------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  39   |   17   |     3      |       4        |    4    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Data Leak](../../../UseCases/uc_data_leak.md) |  dlp-email-alert-in<br> ↳[cisco-se-cef-email-send-receive-success-suser](Ps/pC_ciscosecefemailsendreceivesuccesssuser.md)<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br><br> dlp-email-alert-in-failed<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br> ↳[cisco-secureemail-cef-email-receive-fail-secureemailgateway](Ps/pC_ciscosecureemailcefemailreceivefailsecureemailgateway.md)<br><br> dlp-email-alert-out<br> ↳[cisco-se-cef-email-send-receive-success-suser](Ps/pC_ciscosecefemailsendreceivesuccesssuser.md)<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br><br> dlp-email-alert-out-failed<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br> | [<ul><li>34 Rules</li></ul><ul><li>16 Models</li></ul>](RM/r_m_cisco_cisco_secure_email_Data_Leak.md) |
|   [Malware](../../../UseCases/uc_malware.md)   |  dlp-email-alert-in<br> ↳[cisco-se-cef-email-send-receive-success-suser](Ps/pC_ciscosecefemailsendreceivesuccesssuser.md)<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br><br> dlp-email-alert-in-failed<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br> ↳[cisco-secureemail-cef-email-receive-fail-secureemailgateway](Ps/pC_ciscosecureemailcefemailreceivefailsecureemailgateway.md)<br><br> dlp-email-alert-out<br> ↳[cisco-se-cef-email-send-receive-success-suser](Ps/pC_ciscosecefemailsendreceivesuccesssuser.md)<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br><br> dlp-email-alert-out-failed<br> ↳[cisco-secureemail-cef-email-send-success-logevent](Ps/pC_ciscosecureemailcefemailsendsuccesslogevent.md)<br> | T1190 - Exploit Public Fasing Application<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_cisco_cisco_secure_email_Malware.md)    |
[Next Page -->>](2_ds_cisco_cisco_secure_email.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                            | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                         | Impact |
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br> |        |