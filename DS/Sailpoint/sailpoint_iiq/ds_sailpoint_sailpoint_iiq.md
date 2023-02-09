Vendor: Sailpoint
=================
Product: SailPoint IIQ
----------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|   3   |   1    |         2          |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-change<br> ↳[sailpoint-iiq-json-user-password-modify-success-target](Ps/pC_sailpointiiqjsonuserpasswordmodifysuccesstarget.md)<br> | T1078 - Valid Accounts<br>       | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_sailpoint_sailpoint_iiq_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  account-password-change<br> ↳[sailpoint-iiq-json-user-password-modify-success-target](Ps/pC_sailpointiiqjsonuserpasswordmodifysuccesstarget.md)<br> | T1098 - Account Manipulation<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_sailpoint_sailpoint_iiq_Account_Manipulation.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  account-password-change<br> ↳[sailpoint-iiq-json-user-password-modify-success-target](Ps/pC_sailpointiiqjsonuserpasswordmodifysuccesstarget.md)<br> | T1098 - Account Manipulation<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_sailpoint_sailpoint_iiq_Privilege_Abuse.md)    |

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                      | Execution | Persistence                                                                                                                                  | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |