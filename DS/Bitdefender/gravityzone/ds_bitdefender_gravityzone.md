Vendor: Bitdefender
===================
Product: GravityZone
--------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  94   |   46   |     10     |       3        |    3    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳[bitdefender-gz-json-app-activity-success-registration](Ps/pC_bitdefendergzjsonappactivitysuccessregistration.md)<br><br> app-login<br> ↳[bitdefender-gz-json-app-login-success-gravityzonelogin](Ps/pC_bitdefendergzjsonapploginsuccessgravityzonelogin.md)<br><br> dlp-alert<br> ↳[bitdefender-gz-cef-alert-trigger-success-gravityzone](Ps/pC_bitdefendergzcefalerttriggersuccessgravityzone.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-av](Ps/pC_bitdefendergzjsonalerttriggersuccessav.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-hd](Ps/pC_bitdefendergzjsonalerttriggersuccesshd.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-avc](Ps/pC_bitdefendergzjsonalerttriggersuccessavc.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-aph](Ps/pC_bitdefendergzjsonalerttriggersuccessaph.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>12 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_bitdefender_gravityzone_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  app-activity<br> ↳[bitdefender-gz-json-app-activity-success-registration](Ps/pC_bitdefendergzjsonappactivitysuccessregistration.md)<br><br> app-login<br> ↳[bitdefender-gz-json-app-login-success-gravityzonelogin](Ps/pC_bitdefendergzjsonapploginsuccessgravityzonelogin.md)<br><br> dlp-alert<br> ↳[bitdefender-gz-cef-alert-trigger-success-gravityzone](Ps/pC_bitdefendergzcefalerttriggersuccessgravityzone.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-av](Ps/pC_bitdefendergzjsonalerttriggersuccessav.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-hd](Ps/pC_bitdefendergzjsonalerttriggersuccesshd.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-avc](Ps/pC_bitdefendergzjsonalerttriggersuccessavc.md)<br> ↳[bitdefender-gz-json-alert-trigger-success-aph](Ps/pC_bitdefendergzjsonalerttriggersuccessaph.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_bitdefender_gravityzone_Account_Manipulation.md)    |
[Next Page -->>](2_ds_bitdefender_gravityzone.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                                         | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                                                                                                      | Exfiltration                                                                | Impact |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |