Vendor: VMware
==============
Product: VMware View
--------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  67   |   26   |         7          |       5        |    5    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br><br> authentication-failed<br> ↳[vmware-view-str-app-authentication-fail-rejected](Ps/pC_vmwareviewstrappauthenticationfailrejected.md)<br> ↳[vmware-view-str-app-authentication-fail-denied](Ps/pC_vmwareviewstrappauthenticationfaildenied.md)<br><br> authentication-successful<br> ↳[vmware-view-str-endpoint-login-success-reconnected](Ps/pC_vmwareviewstrendpointloginsuccessreconnected.md)<br> ↳[vmware-view-str-endpoint-authentication-success-application](Ps/pC_vmwareviewstrendpointauthenticationsuccessapplication.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>15 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_vmware_vmware_view_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_view_Account_Manipulation.md)    |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_vmware_vmware_view_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br>    | T1114.003 - Email Collection: Email Forwarding Rule<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_vmware_vmware_view_Data_Leak.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br>    | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_vmware_vmware_view_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_view_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_view_Privileged_Activity.md)    |
[Next Page -->>](2_ds_vmware_vmware_view.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement                                                                     | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br> | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |