Vendor: Teradata
================
Product: Teradata RDBMS
-----------------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  10   |   5    |     1      |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  database-login<br> ↳[teradata-rdbms-str-database-login-success-req8](Ps/pC_teradatardbmsstrdatabaseloginsuccessreq8.md)<br> | T1213 - Data from Information Repositories<br> | [<ul><li>10 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_teradata_teradata_rdbms_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  database-login<br> ↳[teradata-rdbms-str-database-login-success-req8](Ps/pC_teradatardbmsstrdatabaseloginsuccessreq8.md)<br> | T1213 - Data from Information Repositories<br> | [<ul><li>10 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_teradata_teradata_rdbms_Data_Access.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection                                                                              | Command and Control | Exfiltration | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------- | ------------------- | ------------ | ------ |
|                |           |             |                      |                 |                   |           |                  | [Data from Information Repositories](https://attack.mitre.org/techniques/T1213)<br><br> |                     |              |        |