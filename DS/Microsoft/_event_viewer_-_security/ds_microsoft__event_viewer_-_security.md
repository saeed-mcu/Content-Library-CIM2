Vendor: Microsoft
=================
Product:  Event Viewer - Security
---------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  36   |   20   |         9          |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1003 - OS Credential Dumping<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Compromised_Credentials.md)    |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1543.003 - Create or Modify System Process: Windows Service<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Evasion.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1036 - Masquerading<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1543.003 - Create or Modify System Process: Windows Service<br>T1569.002 - T1569.002<br>T1574.010 - T1574.010<br>T1574.011 - T1574.011<br>TA0002 - TA0002<br> | [<ul><li>33 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1053.005 - Scheduled Task/Job: Scheduled Task<br>T1543.003 - Create or Modify System Process: Windows Service<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Privilege_Abuse.md)      |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1543.003 - Create or Modify System Process: Windows Service<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Privilege_Escalation.md) |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  service-created<br> ↳[microsoft-evsecurity-kv-service-create-success-4697-1](Ps/pC_microsoftevsecuritykvservicecreatesuccess46971.md)<br> | T1053.005 - Scheduled Task/Job: Scheduled Task<br>T1543.003 - Create or Modify System Process: Windows Service<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_microsoft__event_viewer_-_security_Privileged_Activity.md)  |

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access | Execution                                                                                                                                                                                                                                                                                                                                                                                                                          | Persistence                                                                                                                                                                                                                                                                                                                                    | Privilege Escalation                                                                                                                                                                                                                  | Defense Evasion                                                                                                                             | Credential Access                                                          | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
|                | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br>[System Services](https://attack.mitre.org/techniques/T1569)<br><br>[Scheduled Task/Job: Scheduled Task](https://attack.mitre.org/techniques/T1053/005)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [Create or Modify System Process](https://attack.mitre.org/techniques/T1543)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br>[Create or Modify System Process: Windows Service](https://attack.mitre.org/techniques/T1543/003)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br> | [Create or Modify System Process](https://attack.mitre.org/techniques/T1543)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br> | [Masquerading](https://attack.mitre.org/techniques/T1036)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           |                  |            |                     |              |        |