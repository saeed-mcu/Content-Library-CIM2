Rules by Product and UseCase
============================
Vendor: SAP
-----------
### Product: [SAP](../ds_sap_sap.md)
### Use-Case: [Privilege Escalation](../../../../UseCases/uc_privilege_escalation.md)

| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|   4   |   1    |     2      |       8        |    8    |

| Event Type   | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>EM-InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions |  • <b>EM-InB-Perm-N</b>: Models users who give mailbox permissions |
| failed-logon | <b>T1210 - Exploitation of Remote Services</b><br> ↳ <b>A-Suspicious-Zerologon</b>: Failed authentication attempt on this asset.    |    |