Vendor: VMware
==============
Product: VMware Horizon
-----------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  90   |   29   |         14         |       5        |    5    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br><br> app-login<br> ↳[vmware-horizon-str-app-login-success-loggedin](Ps/pC_vmwarehorizonstrapploginsuccessloggedin.md)<br><br> authentication-successful<br> ↳[vmware-horizon-str-app-authentication-view](Ps/pC_vmwarehorizonstrappauthenticationview.md)<br> ↳[vmware-horizon-str-endpoint-authentication-success-allocated](Ps/pC_vmwarehorizonstrendpointauthenticationsuccessallocated.md)<br> ↳[vmware-horizon-str-endpoint-authentication-success-requestedpool](Ps/pC_vmwarehorizonstrendpointauthenticationsuccessrequestedpool.md)<br> ↳[vmware-horizon-csv-endpoint-login-success-tunnelservice](Ps/pC_vmwarehorizoncsvendpointloginsuccesstunnelservice.md)<br> ↳[vmware-horizon-csv-endpoint-login-success-user](Ps/pC_vmwarehorizoncsvendpointloginsuccessuser.md)<br><br> failed-logon<br> ↳[vmware-horizon-str-endpoint-login-fail-unable](Ps/pC_vmwarehorizonstrendpointloginfailunable.md)<br> ↳[vmware-horizon-str-endpoint-login-fail-view](Ps/pC_vmwarehorizonstrendpointloginfailview.md)<br> | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>17 Rules</li></ul><ul><li>6 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Account_Manipulation.md)    |
|    [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)    |  failed-logon<br> ↳[vmware-horizon-str-endpoint-login-fail-unable](Ps/pC_vmwarehorizonstrendpointloginfailunable.md)<br> ↳[vmware-horizon-str-endpoint-login-fail-view](Ps/pC_vmwarehorizonstrendpointloginfailview.md)<br>    | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1110 - Brute Force<br>T1110.003 - T1110.003<br>    | [<ul><li>9 Rules</li></ul>](RM/r_m_vmware_vmware_horizon_Brute_Force_Attack.md)    |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br><br> app-login<br> ↳[vmware-horizon-str-app-login-success-loggedin](Ps/pC_vmwarehorizonstrapploginsuccessloggedin.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br>    | T1114.003 - Email Collection: Email Forwarding Rule<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_vmware_vmware_horizon_Data_Leak.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br><br> app-login<br> ↳[vmware-horizon-str-app-login-success-loggedin](Ps/pC_vmwarehorizonstrapploginsuccessloggedin.md)<br><br> failed-logon<br> ↳[vmware-horizon-str-endpoint-login-fail-unable](Ps/pC_vmwarehorizonstrendpointloginfailunable.md)<br> ↳[vmware-horizon-str-endpoint-login-fail-view](Ps/pC_vmwarehorizonstrendpointloginfailview.md)<br>    | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>9 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br><br> failed-logon<br> ↳[vmware-horizon-str-endpoint-login-fail-unable](Ps/pC_vmwarehorizonstrendpointloginfailunable.md)<br> ↳[vmware-horizon-str-endpoint-login-fail-view](Ps/pC_vmwarehorizonstrendpointloginfailview.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1210 - Exploitation of Remote Services<br> | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  app-activity<br> ↳[vmware-horizon-kv-app-activity-success-module](Ps/pC_vmwarehorizonkvappactivitysuccessmodule.md)<br><br> app-login<br> ↳[vmware-horizon-str-app-login-success-loggedin](Ps/pC_vmwarehorizonstrapploginsuccessloggedin.md)<br><br> failed-logon<br> ↳[vmware-horizon-str-endpoint-login-fail-unable](Ps/pC_vmwarehorizonstrendpointloginfailunable.md)<br> ↳[vmware-horizon-str-endpoint-login-fail-view](Ps/pC_vmwarehorizonstrendpointloginfailview.md)<br>    | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_vmware_vmware_horizon_Privileged_Activity.md)    |
[Next Page -->>](2_ds_vmware_vmware_horizon.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                           | Credential Access                                                                                                                                    | Discovery | Lateral Movement                                                                                                                                                                                                                                                                                                                                    | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Use Alternate Authentication Material: Pass the Ticket](https://attack.mitre.org/techniques/T1550/003)<br><br> | [Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br> |           | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |