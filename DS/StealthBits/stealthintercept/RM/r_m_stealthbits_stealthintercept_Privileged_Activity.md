Rules by Product and UseCase
============================
Vendor: StealthBits
-------------------
### Product: [StealthIntercept](../ds_stealthbits_stealthintercept.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|   8   |   2    |         5          |       4        |    0    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| ds-access    | <b>T1207 - Rogue Domain Controller</b><br> ↳ <b>DS-DCShadow-E</b>: Possible DCShadow attack from Existing Machine<br> ↳ <b>DS-DCShadow-F</b>: First event for machine in possible DCShadow attack<br> ↳ <b>A-DS-DCShadow</b>: Possible DCShadow attack by asset detected.<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>DCSync-ExistHost</b>: Possible DCSync attack - existing host has replicated Active Directory.<br> ↳ <b>DCSync-FirstDS</b>: Possible DCSync attack - first DS access event from host.<br> ↳ <b>A-DCSync</b>: Possible DCSync attack detected<br><br><b>T1003.006 - OS Credential Dumping: DCSync</b><br> ↳ <b>DCSync-ExistHost</b>: Possible DCSync attack - existing host has replicated Active Directory.<br> ↳ <b>DCSync-FirstDS</b>: Possible DCSync attack - first DS access event from host.<br> ↳ <b>A-DCSync</b>: Possible DCSync attack detected<br><br><b>T1484 - Group Policy Modification</b><br> ↳ <b>DS-UA</b>: First access to attribute for privileged user |  • <b>DS-HOSTS</b>: Models hosts in an Active Directory environment<br> • <b>DS-UA</b>: Attributes per privileged user |
| file-permission-change | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account    |    |
| file-read    | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account    |    |
| file-write    | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account    |    |