Vendor: Tanium Core Platform
============================
Product: Tanium Core Platform
-----------------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  106  |   45   |     16     |       5        |    5    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  ""file-rename:success""<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> app-activity<br> ↳[tanium-cp-json-app-activity-success-traceconnections](Ps/pC_taniumcpjsonappactivitysuccesstraceconnections.md)<br> ↳[tanium-cp-json-app-activity-success-task](Ps/pC_taniumcpjsonappactivitysuccesstask.md)<br> ↳[tanium-cp-json-app-activity-success-tracesnapshots](Ps/pC_taniumcpjsonappactivitysuccesstracesnapshots.md)<br> ↳[tanium-cp-json-app-activity-success-traceexports](Ps/pC_taniumcpjsonappactivitysuccesstraceexports.md)<br> ↳[tanium-cp-json-app-activity-success-tracemoduleserversettings](Ps/pC_taniumcpjsonappactivitysuccesstracemoduleserversettings.md)<br><br> file-delete<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> file-read<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> file-write<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>12 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_tanium_core_platform_tanium_core_platform_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  ""file-rename:success""<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> app-activity<br> ↳[tanium-cp-json-app-activity-success-traceconnections](Ps/pC_taniumcpjsonappactivitysuccesstraceconnections.md)<br> ↳[tanium-cp-json-app-activity-success-task](Ps/pC_taniumcpjsonappactivitysuccesstask.md)<br> ↳[tanium-cp-json-app-activity-success-tracesnapshots](Ps/pC_taniumcpjsonappactivitysuccesstracesnapshots.md)<br> ↳[tanium-cp-json-app-activity-success-traceexports](Ps/pC_taniumcpjsonappactivitysuccesstraceexports.md)<br> ↳[tanium-cp-json-app-activity-success-tracemoduleserversettings](Ps/pC_taniumcpjsonappactivitysuccesstracemoduleserversettings.md)<br><br> file-delete<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> file-read<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br><br> file-write<br> ↳[tanium-cp-json-file-success-tracefile](Ps/pC_taniumcpjsonfilesuccesstracefile.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_tanium_core_platform_tanium_core_platform_Account_Manipulation.md)    |
[Next Page -->>](2_ds_tanium_core_platform_tanium_core_platform.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Privilege Escalation                                                                                                                                      | Defense Evasion                                                                                                                                                                                                                                    | Credential Access                                                          | Discovery                                                                         | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Server Software Component: Web Shell](https://attack.mitre.org/techniques/T1505/003)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Server Software Component](https://attack.mitre.org/techniques/T1505)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br> | [Indicator Removal on Host: File Deletion](https://attack.mitre.org/techniques/T1070/004)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Indicator Removal on Host](https://attack.mitre.org/techniques/T1070)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Data Destruction](https://attack.mitre.org/techniques/T1485)<br><br>[Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486)<br><br> |