Vendor: Microsoft
=================
Product: Azure Active Directory
-------------------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  61   |   26   |         6          |       4        |    4    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-change<br> ↳[microsoft-azuread-cef-user-password-modify-success-changeuserpassword](Ps/pC_microsoftazureadcefuserpasswordmodifysuccesschangeuserpassword.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-30028](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess30028.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-10024](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess10024.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-10014](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess10014.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-30010](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess30010.md)<br> ↳[microsoft-azuread-json-user-password-modify-success-passwordreset](Ps/pC_microsoftazureadjsonuserpasswordmodifysuccesspasswordreset.md)<br><br> account-password-reset<br> ↳[microsoft-azuread-xml-user-password-reset-success-30009](Ps/pC_microsoftazureadxmluserpasswordresetsuccess30009.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-30029](Ps/pC_microsoftazureadxmluserpasswordresetsuccess30029.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-10015](Ps/pC_microsoftazureadxmluserpasswordresetsuccess10015.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-10025](Ps/pC_microsoftazureadxmluserpasswordresetsuccess10025.md)<br><br> app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>12 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  account-password-change<br> ↳[microsoft-azuread-cef-user-password-modify-success-changeuserpassword](Ps/pC_microsoftazureadcefuserpasswordmodifysuccesschangeuserpassword.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-30028](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess30028.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-10024](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess10024.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-10014](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess10014.md)<br> ↳[microsoft-azuread-xml-user-password-modify-success-30010](Ps/pC_microsoftazureadxmluserpasswordmodifysuccess30010.md)<br> ↳[microsoft-azuread-json-user-password-modify-success-passwordreset](Ps/pC_microsoftazureadjsonuserpasswordmodifysuccesspasswordreset.md)<br><br> account-password-reset<br> ↳[microsoft-azuread-xml-user-password-reset-success-30009](Ps/pC_microsoftazureadxmluserpasswordresetsuccess30009.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-30029](Ps/pC_microsoftazureadxmluserpasswordresetsuccess30029.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-10015](Ps/pC_microsoftazureadxmluserpasswordresetsuccess10015.md)<br> ↳[microsoft-azuread-xml-user-password-reset-success-10025](Ps/pC_microsoftazureadxmluserpasswordresetsuccess10025.md)<br><br> app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br> | T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Account_Manipulation.md)    |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>39 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Compromised_Credentials.md)         |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1114.003 - Email Collection: Email Forwarding Rule<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_microsoft_azure_active_directory_Data_Leak.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br><br> app-activity-failed<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_microsoft_azure_active_directory_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_azure_active_directory_Malware.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br><br> app-activity-failed<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft_azure_active_directory_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br><br> app-activity-failed<br> ↳[microsoft-azuread-json-app-activity-addmembertogroup](Ps/pC_microsoftazureadjsonappactivityaddmembertogroup.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_microsoft_azure_active_directory_Ransomware.md)    |
[Next Page -->>](2_ds_microsoft_azure_active_directory.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |