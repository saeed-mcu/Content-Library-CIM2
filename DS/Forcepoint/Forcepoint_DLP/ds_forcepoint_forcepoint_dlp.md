Vendor: Forcepoint
==================
Product: Forcepoint DLP
-----------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  85   |   33   |     9      |       4        |    4    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  dlp-email-alert-out<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br> ↳[forcepoint-dlp-cef-email-send-success-smtp](Ps/pC_forcepointdlpcefemailsendsuccesssmtp.md)<br><br> dlp-email-alert-out-failed<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br><br> security-alert<br> ↳[forcepoint-dlp-cef-alert-trigger-success-forcepointdlp](Ps/pC_forcepointdlpcefalerttriggersuccessforcepointdlp.md)<br> ↳[forcepoint-dlp-cef-alert-trigger-success-tritonapdata](Ps/pC_forcepointdlpcefalerttriggersuccesstritonapdata.md)<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br><br> usb-insert<br> ↳[forcepoint-dlp-cef-peripheral_storage-insert-success-removablemedia](Ps/pC_forcepointdlpcefperipheral_storageinsertsuccessremovablemedia.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br>    | [<ul><li>25 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_forcepoint_forcepoint_dlp_Compromised_Credentials.md) |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  dlp-email-alert-out<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br> ↳[forcepoint-dlp-cef-email-send-success-smtp](Ps/pC_forcepointdlpcefemailsendsuccesssmtp.md)<br><br> dlp-email-alert-out-failed<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br><br> security-alert<br> ↳[forcepoint-dlp-cef-alert-trigger-success-forcepointdlp](Ps/pC_forcepointdlpcefalerttriggersuccessforcepointdlp.md)<br> ↳[forcepoint-dlp-cef-alert-trigger-success-tritonapdata](Ps/pC_forcepointdlpcefalerttriggersuccesstritonapdata.md)<br> ↳[forcepoint-dlp-cef-email-send-datasecurity](Ps/pC_forcepointdlpcefemailsenddatasecurity.md)<br><br> usb-insert<br> ↳[forcepoint-dlp-cef-peripheral_storage-insert-success-removablemedia](Ps/pC_forcepointdlpcefperipheral_storageinsertsuccessremovablemedia.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1091 - Replication Through Removable Media<br> | [<ul><li>48 Rules</li></ul><ul><li>20 Models</li></ul>](RM/r_m_forcepoint_forcepoint_dlp_Data_Leak.md)    |
[Next Page -->>](2_ds_forcepoint_forcepoint_dlp.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                                                                                                                                 | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                               | Credential Access | Discovery | Lateral Movement                                                                         | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                                                                                                                                                                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------------------------------------------------------------------------------------- | ---------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br>[Replication Through Removable Media](https://attack.mitre.org/techniques/T1091)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           | [Replication Through Removable Media](https://attack.mitre.org/techniques/T1091)<br><br> |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Exfiltration Over Physical Medium: Exfiltration over USB](https://attack.mitre.org/techniques/T1052/001)<br><br>[Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br> |        |