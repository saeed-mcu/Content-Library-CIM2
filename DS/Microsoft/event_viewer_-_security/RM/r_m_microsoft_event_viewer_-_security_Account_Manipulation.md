Rules by Product and UseCase
============================
Vendor: Microsoft
-----------------
### Product: [Event Viewer - Security](../ds_microsoft_event_viewer_-_security.md)
### Use-Case: [Account Manipulation](../../../../UseCases/uc_account_manipulation.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  100  |   47   |         16         |       10       |   10    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| account-creation        | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1136 - Create Account</b><br> ↳ <b>A-ACCT-CR-DEL</b>: Account created and deleted on asset<br> ↳ <b>AC-UH-F</b>: First account creation activity from asset for user<br> ↳ <b>AC-UH-A</b>: Abnormal account creation activity from asset for user<br> ↳ <b>AC-OZ-F</b>: First account creation activity from network zone<br> ↳ <b>AC-OZ-A</b>: Abnormal account creation activity from network zone<br> ↳ <b>AC-OH-F</b>: First account creation activity from asset in the organization<br> ↳ <b>AC-OH-A</b>: Abnormal account creation activity from asset in the organization<br> ↳ <b>AC-UT-TOW-A</b>: Abnormal day for user to perform account creation activity<br> ↳ <b>AM-UA-AC-F</b>: First account creation activity for user<br> ↳ <b>AM-UA-AC-A</b>: Abnormal account creation activity for user<br> ↳ <b>AM-GA-AC-F</b>: First account creation activity for peer group<br> ↳ <b>AM-GA-AC-A</b>: Abnormal account creation activity for peer group<br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1136.001 - Create Account: Create: Local Account</b><br> ↳ <b>A-AC-DhU-system-F</b>: First account creation by system account on asset<br> ↳ <b>A-AC-DhU-system-A</b>: Abnormal account creation by system account on asset<br> ↳ <b>AC-LocUA-F-new</b>: First account creation activity by a new local user<br> ↳ <b>AC-LocUA-A</b>: Abnormal account creation activity by local user<br><br><b>T1136.002 - T1136.002</b><br> ↳ <b>AM-UD-F</b>: First account creation on domain for user<br> ↳ <b>AM-UD-A</b>: Abnormal account creation on domain for user    |  • <b>AE-GA</b>: All activity for peer groups<br> • <b>AE-UA</b>: All activity for users<br> • <b>AC-UT-TOW</b>: Account creation activity time for user<br> • <b>AM-UD</b>: Account creation on domain by user<br> • <b>AC-OH</b>: Account creation hosts in organization<br> • <b>AC-OZ</b>: Account creation activity from zone<br> • <b>AC-UH</b>: Account creation activity on host for user<br> • <b>A-AC-DhU-system</b>: System accounts performing account creation activities    |
| account-deleted         | <b>T1531 - Account Access Removal</b><br> ↳ <b>AM-UA-AD-F</b>: First account deletion activity for user<br><br><b>T1136 - Create Account</b><br> ↳ <b>A-ACCT-CR-DEL</b>: Account created and deleted on asset    |  • <b>AE-UA</b>: All activity for users    |
| account-password-change | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-UA-APLocU-F</b>: First account password change for local user    |    |
| account-password-reset  | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-UA-APLocU-F</b>: First account password change for local user    |    |
| app-activity    | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>EM-InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions    |  • <b>EM-InB-Perm-N</b>: Models users who give mailbox permissions    |
| ds-access    | <b>T1207 - Rogue Domain Controller</b><br> ↳ <b>A-DS-Replication</b>: First time a new server replicated itself on this asset<br> ↳ <b>DS-DCSh-Add</b>: Directory service server object added<br> ↳ <b>DS-DCSh-Del</b>: Directory service server object created and deleted<br><br><b>T1484 - Group Policy Modification</b><br> ↳ <b>DS-OU-F</b>: First directory service event for user in the organization<br> ↳ <b>DS-OG-F</b>: First directory service event for user in the peer group<br> ↳ <b>DS-OAT-F</b>: First directory service activity type for object class<br> ↳ <b>DS-OAT-A</b>: Abnormal directory service activity type for object class<br> ↳ <b>DS-UAT-F</b>: First directory service activity type for user per object class<br> ↳ <b>DS-UAT-A</b>: Abnormal directory service activity type for user per object class<br> ↳ <b>DS-OOC-F</b>: First directory service object class for organization<br> ↳ <b>DS-OOC-A</b>: Abnormal directory service object class for organization<br> ↳ <b>DS-GOC-F</b>: First directory service object class for peer group<br> ↳ <b>DS-GOC-A</b>: Abnormal directory service object class for peer group<br> ↳ <b>DS-UOC-F</b>: First directory service object class for user<br> ↳ <b>DS-UOC-A</b>: Abnormal directory service object class for user<br> ↳ <b>DS-APRIV</b>: Non-Privileged user accessing privileged directory service attribute<br> ↳ <b>DS-UA</b>: First access to attribute for privileged user<br> ↳ <b>DS-OH-F</b>: First directory service activity on host for organization<br> ↳ <b>DS-OH-A</b>: Abnormal directory service activity on host for organization<br> ↳ <b>DS-GH-F</b>: First directory service activity on host for peer group<br> ↳ <b>DS-GH-A</b>: Abnormal directory service activity on host for peer group<br> ↳ <b>DS-UH-F</b>: First directory service activity on host for user<br> ↳ <b>DS-UH-A</b>: Abnormal directory service activity on host for user<br> ↳ <b>DS-OSZ-F</b>: First directory service activity from source zone for organization<br> ↳ <b>DS-OSZ-A</b>: Abnormal directory service activity from source zone for organization<br> ↳ <b>DS-GSZ-F</b>: First directory service activity from source zone for peer group<br> ↳ <b>DS-GSZ-A</b>: Abnormal directory service activity from source zone for peer group<br> ↳ <b>DS-USZ-F</b>: First directory service activity from source zone for user<br> ↳ <b>DS-USZ-A</b>: Abnormal directory service activity from source zone for user<br> ↳ <b>DS-USH-F</b>: First directory service activity on source host for user<br> ↳ <b>DS-USH-A</b>: Abnormal directory service activity on source host for user    |  • <b>DS-USH</b>: Source hosts with directory service activity for user<br> • <b>DS-USZ</b>: Source network zones with directory service activity for the user<br> • <b>DS-GSZ</b>: Source network zones with directory service activity in the peer group<br> • <b>DS-OSZ</b>: Source network zones with directory service activity in the organization<br> • <b>DS-UH</b>: Hosts with directory service activity in the user<br> • <b>DS-GH</b>: Hosts with directory service activity in the peer group<br> • <b>DS-OH</b>: Hosts with directory service activity in the organization<br> • <b>DS-UA</b>: Attributes per privileged user<br> • <b>DS-APRIV</b>: Privileged user attributes<br> • <b>DS-UOC</b>: Directory service object classes for user<br> • <b>DS-GOC</b>: Directory service object classes in the peer group<br> • <b>DS-OOC</b>: Directory service object classes in the organization<br> • <b>DS-UAT-new</b>: Directory services activity types for user per object class<br> • <b>DS-OAT-new</b>: Directory services activity types per object class<br> • <b>DS-OG</b>: Users with directory service activity in the peer group<br> • <b>DS-OU</b>: Users with directory service activity in the organization |
| member-added    | <b>T1098 - Account Manipulation</b><br> ↳ <b>A-GM-DhU-system-F</b>: First group management by system account on asset<br> ↳ <b>GM-LocUA-F-new</b>: First group management activity by a new local user<br> ↳ <b>GM-LocUA-A</b>: Abnormal group management activity by local user<br> ↳ <b>MA-SELF</b>: User added themself to a group<br> ↳ <b>MA-PRIV-F-local</b>: First addition to privileged group by local user<br> ↳ <b>MA-PRIV-A</b>: Abnormal addition to privileged group by user<br> ↳ <b>GM-UH-F</b>: First group management activity from asset for user<br> ↳ <b>GM-UH-A</b>: Abnormal group management activity from asset for user<br> ↳ <b>GM-OZ-F</b>: First group management activity from network zone<br> ↳ <b>GM-OZ-A</b>: Abnormal group management activity from network zone<br> ↳ <b>GM-OH-F</b>: First group management activity from asset in the organization<br> ↳ <b>GM-OH-A</b>: Abnormal group management activity from asset in the organization<br> ↳ <b>GM-UT-TOW-A</b>: Abnormal day for user to perform group management activity<br> ↳ <b>AM-GA-MA-F</b>: First account group management activity for peer group<br> ↳ <b>AM-OU-SS-F</b>: First addition and removal of member from a group by user in a single session for organization<br> ↳ <b>AM-OU-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the organization<br> ↳ <b>AM-OG-SS-F</b>: First addition and removal of member from a group by user in a single session for peer group<br> ↳ <b>AM-OG-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the peer group<br> ↳ <b>AM-OG-F</b>: First member addition to this group for the organization<br> ↳ <b>AM-OG-A</b>: Abnormal account addition to this group for the organization<br> ↳ <b>AM-GOU-F</b>: First account OU addition to this group<br> ↳ <b>AM-GOU-A</b>: Abnormal account OU addition to this group<br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1136 - Create Account</b><br> ↳ <b>AM-UA-MA-F-new</b>: Account management activity for new user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user    |  • <b>AE-GA</b>: All activity for peer groups<br> • <b>AM-GOU</b>: Account management, OUs that are added to security groups<br> • <b>AM-AG</b>: Account management, groups which users are being added to<br> • <b>AM-OG-SS</b>: Models the peer groups who perform addition and removal of members from group in same session<br> • <b>AM-OU-SS</b>: Models the users who perform addition and removal of members from group in same session in the organization<br> • <b>AE-UA</b>: All activity for users<br> • <b>GM-UT-TOW</b>: Group management activity time for user<br> • <b>GM-OH</b>: Group management hosts in organization<br> • <b>GM-OZ</b>: Group management activity from zone<br> • <b>GM-UH</b>: Group management activity on host for user<br> • <b>AM-OU-PG</b>: Account group management of high privileges in the organization<br> • <b>A-GM-DhU-system</b>: System accounts performing group management activities    |
| member-removed          | <b>T1098 - Account Manipulation</b><br> ↳ <b>GM-LocUA-F-new</b>: First group management activity by a new local user<br> ↳ <b>GM-LocUA-A</b>: Abnormal group management activity by local user<br> ↳ <b>GM-UH-F</b>: First group management activity from asset for user<br> ↳ <b>GM-UH-A</b>: Abnormal group management activity from asset for user<br> ↳ <b>GM-OZ-F</b>: First group management activity from network zone<br> ↳ <b>GM-OZ-A</b>: Abnormal group management activity from network zone<br> ↳ <b>GM-OH-F</b>: First group management activity from asset in the organization<br> ↳ <b>GM-OH-A</b>: Abnormal group management activity from asset in the organization<br> ↳ <b>GM-UT-TOW-A</b>: Abnormal day for user to perform group management activity<br> ↳ <b>AM-UA-MA-F</b>: First account group management activity for user<br> ↳ <b>AM-GA-MA-F</b>: First account group management activity for peer group<br> ↳ <b>AM-OU-SS-F</b>: First addition and removal of member from a group by user in a single session for organization<br> ↳ <b>AM-OU-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the organization<br> ↳ <b>AM-OG-SS-F</b>: First addition and removal of member from a group by user in a single session for peer group<br> ↳ <b>AM-OG-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the peer group    |  • <b>AM-OG-SS</b>: Models the peer groups who perform addition and removal of members from group in same session<br> • <b>AM-OU-SS</b>: Models the users who perform addition and removal of members from group in same session in the organization<br> • <b>AE-GA</b>: All activity for peer groups<br> • <b>AE-UA</b>: All activity for users<br> • <b>GM-UT-TOW</b>: Group management activity time for user<br> • <b>GM-OH</b>: Group management hosts in organization<br> • <b>GM-OZ</b>: Group management activity from zone<br> • <b>GM-UH</b>: Group management activity on host for user    |
| process-created         | <b>T1531 - Account Access Removal</b><br> ↳ <b>NET-EXE-DELETE-ORG-F</b>: First time net.exe has been used to delete a user account by this user.<br> ↳ <b>NET-EXE-DELETE-ORG-A</b>: Abnormal usage of net.exe to delete a user account by this user.<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>NET-EXE-ADD-GRP-ORG-F</b>: First time net.exe has been used to create/add to a group by this user.<br> ↳ <b>NET-EXE-ADD-GRP-ORG-A</b>: Abnormal usage of net.exe to create/add to a group by this user.<br> ↳ <b>NET-EXE-ACTIVE-ORG-F</b>: First time net.exe has been used to disable/enable a user account by this user.<br> ↳ <b>NET-EXE-ACTIVE-ORG-A</b>: Abnormal usage of net.exe to disable/enable a user account by this user.<br><br><b>T1098 - Account Manipulation</b><br> ↳ <b>NET-EXE-ADD-GRP-ORG-F</b>: First time net.exe has been used to create/add to a group by this user.<br> ↳ <b>NET-EXE-ADD-GRP-ORG-A</b>: Abnormal usage of net.exe to create/add to a group by this user.<br> ↳ <b>NET-EXE-ACTIVE-ORG-F</b>: First time net.exe has been used to disable/enable a user account by this user.<br> ↳ <b>NET-EXE-ACTIVE-ORG-A</b>: Abnormal usage of net.exe to disable/enable a user account by this user.<br><br><b>T1136 - Create Account</b><br> ↳ <b>NET-EXE-ADD-GRP-ORG-F</b>: First time net.exe has been used to create/add to a group by this user.<br> ↳ <b>NET-EXE-ADD-GRP-ORG-A</b>: Abnormal usage of net.exe to create/add to a group by this user.<br><br><b>T1136.001 - Create Account: Create: Local Account</b><br> ↳ <b>AC-OZ-CLI-F</b>: First zone on which account was created using CLI command<br> ↳ <b>AC-OH-CLI-F</b>: First host on which account was created using CLI command<br> ↳ <b>NET-EXE-ADD-ORG-F</b>: First time net.exe has been used to create a user account by this user.<br> ↳ <b>NET-EXE-ADD-ORG-A</b>: Abnormal usage of net.exe to create a user account by this user.<br><br><b>T1021.003 - T1021.003</b><br> ↳ <b>A-MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable on this asset.<br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1059.001 - Command and Scripting Interperter: PowerShell</b><br> ↳ <b>A-MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable on this asset.<br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1059.003 - T1059.003</b><br> ↳ <b>A-MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable on this asset.<br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1218.010 - Signed Binary Proxy Execution: Regsvr32</b><br> ↳ <b>A-MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable on this asset.<br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1559.002 - T1559.002</b><br> ↳ <b>A-MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable on this asset.<br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>A-ShadowCP-SymLink</b>: Shadow Copies Access via Symlink on this asset<br> ↳ <b>ShadowCP-SymLink</b>: Shadow Copies Access via Symlink<br><br><b>T1003.003 - T1003.003</b><br> ↳ <b>A-AD-Diagnostic-Tool</b>: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe) on this asset |  • <b>NET-EXE-DELETE-ORG</b>: Using net.exe to delete a user account<br> • <b>NET-EXE-ACTIVE-ORG</b>: Using net.exe to disable/enable a user account<br> • <b>NET-EXE-ADD-GRP-ORG</b>: Using net.exe to add a group account<br> • <b>NET-EXE-ADD-ORG</b>: Using net.exe to add a user account<br> • <b>AC-OH-CLI</b>: Hosts on which account was created using CLI command<br> • <b>AC-OZ-CLI</b>: Zones on which account was created using CLI command    |
| vpn-logout    | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Perm-A</b>: Abnormal number of mailbox permission given by user.<br><br><b>T1484 - Group Policy Modification</b><br> ↳ <b>FDS-Count</b>: Abnormal number of failed directory service events in the organization<br> ↳ <b>FDS-GCount</b>: Abnormal number of failed directory service events in the peer group<br> ↳ <b>FDS-UCount</b>: Abnormal number of failed directory service events in the user<br> ↳ <b>DS-Count</b>: Abnormal number of directory service events in the organization<br> ↳ <b>DS-GCount</b>: Abnormal number of directory service events in the peer group<br> ↳ <b>DS-UCount</b>: Abnormal number of directory service events in the user    |  • <b>EM-InB-Perm</b>: Models the number of mailbox permissions given by this user.<br> • <b>DS-UCount</b>: Count of directory service activity events in the user<br> • <b>DS-GCount</b>: Count of directory service activity events in the peer group<br> • <b>DS-Count</b>: Count of directory service activity events in the organization<br> • <b>FDS-UCount</b>: Count of failed directory service activity events in the user<br> • <b>FDS-GCount</b>: Count of failed directory service activity events in the peer group<br> • <b>FDS-Count</b>: Count of failed directory service activity events in the organization    |