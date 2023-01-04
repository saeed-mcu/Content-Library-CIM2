Vendor: Exabeam
===============
Product: Advanced Analytics
---------------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  33   |   20   |     4      |       2        |    2    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md) |  ""app-notification:success""<br> ↳[exabeam-aa-json-app-notification-queue](Ps/pC_exabeamaajsonappnotificationqueue.md)<br><br> dlp-alert<br> ↳[exabeam-aa-kv-alert-trigger-success-anomaly](Ps/pC_exabeamaakvalerttriggersuccessanomaly.md)<br> ↳[exabeam-aa-kv-alert-trigger-exaanalyticsmaster](Ps/pC_exabeamaakvalerttriggerexaanalyticsmaster.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br> | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_exabeam_advanced_analytics_Data_Exfiltration.md) |
|         [Data Leak](../../../UseCases/uc_data_leak.md)         |  ""app-notification:success""<br> ↳[exabeam-aa-json-app-notification-queue](Ps/pC_exabeamaajsonappnotificationqueue.md)<br><br> dlp-alert<br> ↳[exabeam-aa-kv-alert-trigger-success-anomaly](Ps/pC_exabeamaakvalerttriggersuccessanomaly.md)<br> ↳[exabeam-aa-kv-alert-trigger-exaanalyticsmaster](Ps/pC_exabeamaakvalerttriggerexaanalyticsmaster.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br> | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_exabeam_advanced_analytics_Data_Leak.md)         |
|    [Malware](../../../UseCases/uc_malware.md)    |  ""app-notification:success""<br> ↳[exabeam-aa-json-app-notification-queue](Ps/pC_exabeamaajsonappnotificationqueue.md)<br><br> dlp-alert<br> ↳[exabeam-aa-kv-alert-trigger-success-anomaly](Ps/pC_exabeamaakvalerttriggersuccessanomaly.md)<br> ↳[exabeam-aa-kv-alert-trigger-exaanalyticsmaster](Ps/pC_exabeamaakvalerttriggerexaanalyticsmaster.md)<br> | TA0002 - TA0002<br>    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_exabeam_advanced_analytics_Malware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                             | Exfiltration                                                                | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------ |
|                |           |             |                      |                 |                   |           |                  |            | [Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |