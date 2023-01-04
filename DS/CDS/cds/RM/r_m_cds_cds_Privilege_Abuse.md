Rules by Product and UseCase
============================
Vendor: CDS
-----------
### Product: [CDS](../ds_cds_cds.md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  22   |   7    |     5      |       4        |    4    |

| Event Type       | Rules    | Models    |
| ---- | ---- | ---- |
| account-creation | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1136 - Create Account</b><br> ↳ <b>AC-UH-F</b>: First account creation activity from asset for user<br> ↳ <b>AC-UH-A</b>: Abnormal account creation activity from asset for user<br> ↳ <b>AC-OZ-F</b>: First account creation activity from network zone<br> ↳ <b>AC-OZ-A</b>: Abnormal account creation activity from network zone<br> ↳ <b>AC-OH-F</b>: First account creation activity from asset in the organization<br> ↳ <b>AC-OH-A</b>: Abnormal account creation activity from asset in the organization<br> ↳ <b>AC-UT-TOW-A</b>: Abnormal day for user to perform account creation activity<br> ↳ <b>AM-UA-AC-F</b>: First account creation activity for user<br> ↳ <b>AM-UA-AC-A</b>: Abnormal account creation activity for user<br> ↳ <b>AM-GA-AC-F</b>: First account creation activity for peer group<br> ↳ <b>AM-GA-AC-A</b>: Abnormal account creation activity for peer group<br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1136.001 - Create Account: Create: Local Account</b><br> ↳ <b>AC-LocUA-F-new</b>: First account creation activity by a new local user<br> ↳ <b>AC-LocUA-A</b>: Abnormal account creation activity by local user<br><br><b>T1136.002 - T1136.002</b><br> ↳ <b>AM-UD-F</b>: First account creation on domain for user<br> ↳ <b>AM-UD-A</b>: Abnormal account creation on domain for user |  • <b>AE-GA</b>: All activity for peer groups<br> • <b>AE-UA</b>: All activity for users<br> • <b>AC-UT-TOW</b>: Account creation activity time for user<br> • <b>AM-UD</b>: Account creation on domain by user<br> • <b>AC-OH</b>: Account creation hosts in organization<br> • <b>AC-OZ</b>: Account creation activity from zone<br> • <b>AC-UH</b>: Account creation activity on host for user |
| account-switch   | <b>T1078 - Valid Accounts</b><br> ↳ <b>AS-UA-F-PRIV</b>: Account switch to a privileged or executive account<br> ↳ <b>DC18-New</b>: New account switch to privileged account    |    |
| failed-logon     | <b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-04</b>: Failed logon by a service account<br> ↳ <b>SEQ-UH-05</b>: Failed interactive logon by a service account<br> ↳ <b>SEQ-UH-12</b>: Logon attempt on a disabled account    |  • <b>AE-UA</b>: All activity for users    |