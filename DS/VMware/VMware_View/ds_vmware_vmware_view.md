Vendor: VMware
==============
Product: VMware View
--------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  76   |   31   |     7      |       9        |    9    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  ""app-logout:success""<br> ↳[vmware-view-kv-app-logout-success-userloggedout](Ps/pC_vmwareviewkvapplogoutsuccessuserloggedout.md)<br> ↳[vmware-view-str-app-logout-success-loggedoff](Ps/pC_vmwareviewstrapplogoutsuccessloggedoff.md)<br> ↳[vmware-view-str-app-logout-success-loggedout](Ps/pC_vmwareviewstrapplogoutsuccessloggedout.md)<br><br> ""app-notification:success""<br> ↳[vmware-view-str-app-notification-expired](Ps/pC_vmwareviewstrappnotificationexpired.md)<br> ↳[vmware-view-str-app-notification-success-connection](Ps/pC_vmwareviewstrappnotificationsuccessconnection.md)<br> ↳[vmware-view-str-app-notification-success-shutdown](Ps/pC_vmwareviewstrappnotificationsuccessshutdown.md)<br> ↳[vmware-view-str-app-notification-success-reconfigured](Ps/pC_vmwareviewstrappnotificationsuccessreconfigured.md)<br><br> ""endpoint-delete:success""<br> ↳[vmware-view-str-endpoint-delete-success-deleted](Ps/pC_vmwareviewstrendpointdeletesuccessdeleted.md)<br><br> app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br><br> authentication-failed<br> ↳[vmware-view-str-app-authentication-fail-rejected](Ps/pC_vmwareviewstrappauthenticationfailrejected.md)<br> ↳[vmware-view-str-app-authentication-fail-denied](Ps/pC_vmwareviewstrappauthenticationfaildenied.md)<br><br> computer-logon<br> ↳[vmware-view-str-endpoint-login-success-reconnected](Ps/pC_vmwareviewstrendpointloginsuccessreconnected.md)<br><br> nac-logon<br> ↳[vmware-view-str-endpoint-authentication-success-application](Ps/pC_vmwareviewstrendpointauthenticationsuccessapplication.md)<br><br> winsession-disconnect<br> ↳[vmware-view-str-endpoint-logout-success-disconnected](Ps/pC_vmwareviewstrendpointlogoutsuccessdisconnected.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>21 Rules</li></ul><ul><li>7 Models</li></ul>](RM/r_m_vmware_vmware_view_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  ""app-logout:success""<br> ↳[vmware-view-kv-app-logout-success-userloggedout](Ps/pC_vmwareviewkvapplogoutsuccessuserloggedout.md)<br> ↳[vmware-view-str-app-logout-success-loggedoff](Ps/pC_vmwareviewstrapplogoutsuccessloggedoff.md)<br> ↳[vmware-view-str-app-logout-success-loggedout](Ps/pC_vmwareviewstrapplogoutsuccessloggedout.md)<br><br> ""app-notification:success""<br> ↳[vmware-view-str-app-notification-expired](Ps/pC_vmwareviewstrappnotificationexpired.md)<br> ↳[vmware-view-str-app-notification-success-connection](Ps/pC_vmwareviewstrappnotificationsuccessconnection.md)<br> ↳[vmware-view-str-app-notification-success-shutdown](Ps/pC_vmwareviewstrappnotificationsuccessshutdown.md)<br> ↳[vmware-view-str-app-notification-success-reconfigured](Ps/pC_vmwareviewstrappnotificationsuccessreconfigured.md)<br><br> ""endpoint-delete:success""<br> ↳[vmware-view-str-endpoint-delete-success-deleted](Ps/pC_vmwareviewstrendpointdeletesuccessdeleted.md)<br><br> app-activity<br> ↳[vmware-view-str-app-activity-success-application](Ps/pC_vmwareviewstrappactivitysuccessapplication.md)<br><br> app-login<br> ↳[vmware-view-str-app-login-success-viewuser](Ps/pC_vmwareviewstrapploginsuccessviewuser.md)<br><br> authentication-failed<br> ↳[vmware-view-str-app-authentication-fail-rejected](Ps/pC_vmwareviewstrappauthenticationfailrejected.md)<br> ↳[vmware-view-str-app-authentication-fail-denied](Ps/pC_vmwareviewstrappauthenticationfaildenied.md)<br><br> computer-logon<br> ↳[vmware-view-str-endpoint-login-success-reconnected](Ps/pC_vmwareviewstrendpointloginsuccessreconnected.md)<br><br> nac-logon<br> ↳[vmware-view-str-endpoint-authentication-success-application](Ps/pC_vmwareviewstrendpointauthenticationsuccessapplication.md)<br><br> winsession-disconnect<br> ↳[vmware-view-str-endpoint-logout-success-disconnected](Ps/pC_vmwareviewstrendpointlogoutsuccessdisconnected.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_view_Account_Manipulation.md)    |
[Next Page -->>](2_ds_vmware_vmware_view.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement                                                     | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br> | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |