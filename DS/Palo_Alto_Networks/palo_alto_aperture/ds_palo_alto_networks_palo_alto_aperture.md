Vendor: Palo Alto Networks
==========================
Product: Palo Alto Aperture
---------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  33   |   20   |         4          |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md) |  dlp-alert<br> ↳[pan-aperture-sk4-alert-trigger-success-incident](Ps/pC_panaperturesk4alerttriggersuccessincident.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-policyviolation](Ps/pC_panaperturesk4alerttriggersuccesspolicyviolation.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-incident-1](Ps/pC_panaperturesk4alerttriggersuccessincident1.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br> | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_palo_alto_networks_palo_alto_aperture_Data_Exfiltration.md) |
|         [Data Leak](../../../UseCases/uc_data_leak.md)         |  dlp-alert<br> ↳[pan-aperture-sk4-alert-trigger-success-incident](Ps/pC_panaperturesk4alerttriggersuccessincident.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-policyviolation](Ps/pC_panaperturesk4alerttriggersuccesspolicyviolation.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-incident-1](Ps/pC_panaperturesk4alerttriggersuccessincident1.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br> | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_palo_alto_networks_palo_alto_aperture_Data_Leak.md)         |
|    [Malware](../../../UseCases/uc_malware.md)    |  dlp-alert<br> ↳[pan-aperture-sk4-alert-trigger-success-incident](Ps/pC_panaperturesk4alerttriggersuccessincident.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-policyviolation](Ps/pC_panaperturesk4alerttriggersuccesspolicyviolation.md)<br> ↳[pan-aperture-sk4-alert-trigger-success-incident-1](Ps/pC_panaperturesk4alerttriggersuccessincident1.md)<br> | TA0002 - TA0002<br>    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_palo_alto_networks_palo_alto_aperture_Malware.md)    |

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                             | Exfiltration                                                                | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------ |
|                |           |             |                      |                 |                   |           |                  |            | [Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |