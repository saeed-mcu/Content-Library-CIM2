Vendor: LOGBinder
=================
Product: LOGBinder for SharePoint
---------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  114  |   52   |         14         |       3        |    0    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>12 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Account_Manipulation.md)    |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-read<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br> | T1003.001 - T1003.001<br>T1003.002 - T1003.002<br>T1003.003 - T1003.003<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br> | [<ul><li>82 Rules</li></ul><ul><li>45 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Compromised_Credentials.md)         |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-read<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>54 Rules</li></ul><ul><li>31 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Data_Access.md)    |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | TA0002 - TA0002<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Data_Exfiltration.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1114.001 - T1114.001<br>T1114.003 - Email Collection: Email Forwarding Rule<br>    | [<ul><li>4 Rules</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Data_Leak.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1003.002 - T1003.002<br>T1078 - Valid Accounts<br>T1505.003 - Server Software Component: Web Shell<br>T1547.001 - T1547.001<br>TA0002 - TA0002<br>    | [<ul><li>11 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Malware.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-read<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>10 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-read<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>6 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br><br> file-write<br> ↳[logbinder-sharepoint-cef-file-app-fname](Ps/pC_logbindersharepointceffileappfname.md)<br>    | T1078 - Valid Accounts<br>T1486 - Data Encrypted for Impact<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_logbinder_logbinder_for_sharepoint_Ransomware.md)    |

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Privilege Escalation                                                                                                                                      | Defense Evasion                                                     | Credential Access                                                          | Discovery                                                                         | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Server Software Component: Web Shell](https://attack.mitre.org/techniques/T1505/003)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Server Software Component](https://attack.mitre.org/techniques/T1505)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486)<br><br> |