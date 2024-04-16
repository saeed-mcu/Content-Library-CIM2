Vendor: FireEye
===============
Product: FireEye Email MPS
--------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  106  |   39   |         21         |       2        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>    | [<ul><li>7 Rules</li></ul><ul><li>7 Models</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  security-alert<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br> ↳[fireeye-emailgateway-json-alert-trigger-success-emailmps](Ps/pC_fireeyeemailgatewayjsonalerttriggersuccessemailmps.md)<br> ↳[fireeye-emailgateway-json-alert-trigger-success-emailmps](Ps/pC_fireeyeemailgatewayjsonalerttriggersuccessemailmps.md)<br><br> web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1071 - Application Layer Protocol<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1078 - Valid Accounts<br>T1102 - Web Service<br>T1133 - External Remote Services<br>T1189 - Drive-by Compromise<br>T1190 - Exploit Public Fasing Application<br>T1204.001 - T1204.001<br>T1566.002 - Phishing: Spearphishing Link<br>T1568.002 - Dynamic Resolution: Domain Generation Algorithms<br> | [<ul><li>63 Rules</li></ul><ul><li>32 Models</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Compromised_Credentials.md)        |
|    [Cryptomining](../../../UseCases/uc_cryptomining.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>T1496 - Resource Hijacking<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Cryptomining.md)    |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1041 - Exfiltration Over C2 Channel<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1567 - Exfiltration Over Web Service<br>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage<br>T1568 - Dynamic Resolution<br>T1568.002 - Dynamic Resolution: Domain Generation Algorithms<br>    | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Data_Exfiltration.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1041 - Exfiltration Over C2 Channel<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1567 - Exfiltration Over Web Service<br>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage<br>    | [<ul><li>5 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Data_Leak.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1189 - Drive-by Compromise<br>T1204.001 - T1204.001<br>T1534 - Internal Spearphishing<br>T1566.002 - Phishing: Spearphishing Link<br>T1598.003 - T1598.003<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Phishing.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Privilege_Abuse.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>TA0011 - TA0011<br>    | [<ul><li>4 Rules</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Ransomware.md)    |
|    [Workforce Protection](../../../UseCases/uc_workforce_protection.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-suser](Ps/pC_fireeyenetworksecuritycefalerttriggersuccesssuser.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_email_mps_Workforce_Protection.md)    |
[Next Page -->>](2_ds_fireeye_fireeye_email_mps.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Execution                                                                                                                                                                                                                                                       | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                               | Credential Access | Discovery | Lateral Movement                                                            | Collection | Command and Control                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Exfiltration                                                                                                                                                                                                                                                                             | Impact                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | --------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [Phishing: Spearphishing Link](https://attack.mitre.org/techniques/T1566/002)<br><br>[External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Drive-by Compromise](https://attack.mitre.org/techniques/T1189)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br>[Phishing](https://attack.mitre.org/techniques/T1566)<br><br> | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[User Execution](https://attack.mitre.org/techniques/T1204)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           | [Internal Spearphishing](https://attack.mitre.org/techniques/T1534)<br><br> |            | [Web Service](https://attack.mitre.org/techniques/T1102)<br><br>[Application Layer Protocol: Web Protocols](https://attack.mitre.org/techniques/T1071/001)<br><br>[Dynamic Resolution](https://attack.mitre.org/techniques/T1568)<br><br>[Dynamic Resolution: Domain Generation Algorithms](https://attack.mitre.org/techniques/T1568/002)<br><br>[Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over C2 Channel](https://attack.mitre.org/techniques/T1041)<br><br>[Exfiltration Over Web Service: Exfiltration to Cloud Storage](https://attack.mitre.org/techniques/T1567/002)<br><br>[Exfiltration Over Web Service](https://attack.mitre.org/techniques/T1567)<br><br> | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |