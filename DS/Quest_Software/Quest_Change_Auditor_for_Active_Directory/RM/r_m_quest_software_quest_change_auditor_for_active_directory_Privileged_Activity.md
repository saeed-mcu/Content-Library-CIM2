Vendor: Quest Software
======================
### Product: [Quest Change Auditor for Active Directory](../ds_quest_software_quest_change_auditor_for_active_directory.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|   9   |   3    |     4      |       11       |   11    |

| Event Type   | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity    |  • <b>APP-AT-PRIV</b>: Privileged application activities    |
| ds-access    | <b>T1207 - Rogue Domain Controller</b><br> ↳ <b>A-DS-DCShadow</b>: Possible DCShadow attack by asset detected.<br> ↳ <b>DS-DCShadow-E</b>: Possible DCShadow attack from Existing Machine<br> ↳ <b>DS-DCShadow-F</b>: First event for machine in possible DCShadow attack<br><br><b>T1484 - Group Policy Modification</b><br> ↳ <b>DS-UA</b>: First access to attribute for privileged user<br><br><b>T1003.006 - OS Credential Dumping: DCSync</b><br> ↳ <b>A-DCSync</b>: Possible DCSync Attack: New domain controller detected<br> ↳ <b>DCSync-ExistHost</b>: Possible DCSync attack - existing host has replicated Active Directory.<br> ↳ <b>DCSync-FirstDS</b>: Possible DCSync attack - first DS access event from host. |  • <b>DS-HOSTS</b>: Models hosts in an Active Directory environment<br> • <b>DS-UA</b>: Attributes per privileged user |