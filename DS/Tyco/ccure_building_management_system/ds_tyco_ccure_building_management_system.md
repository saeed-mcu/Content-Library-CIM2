Vendor: Tyco
============
Product: CCURE Building Management System
-----------------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  50   |   22   |         4          |       2        |    2    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br><br> failed-physical-access<br> ↳[tyco-ccure-kv-physical-location-access-vendoraction](Ps/pC_tycoccurekvphysicallocationaccessvendoraction.md)<br> ↳[tyco-ccure-xml-physical-location-access-fail-card](Ps/pC_tycoccurexmlphysicallocationaccessfailcard.md)<br><br> physical-access<br> ↳[tyco-ccure-kv-physical-location-access-vendoraction](Ps/pC_tycoccurekvphysicallocationaccessvendoraction.md)<br> ↳[tyco-ccure-xml-physical-location-access-fail-card](Ps/pC_tycoccurexmlphysicallocationaccessfailcard.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>13 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_tyco_ccure_building_management_system_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br> | [<ul><li>27 Rules</li></ul><ul><li>16 Models</li></ul>](RM/r_m_tyco_ccure_building_management_system_Compromised_Credentials.md)         |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>5 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_tyco_ccure_building_management_system_Data_Access.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_tyco_ccure_building_management_system_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_tyco_ccure_building_management_system_Malware.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_tyco_ccure_building_management_system_Privilege_Abuse.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-login<br> ↳[tyco-ccure-cef-app-login-success-operatorlogin](Ps/pC_tycoccurecefapploginsuccessoperatorlogin.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_tyco_ccure_building_management_system_Ransomware.md)    |
[Next Page -->>](2_ds_tyco_ccure_building_management_system.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |