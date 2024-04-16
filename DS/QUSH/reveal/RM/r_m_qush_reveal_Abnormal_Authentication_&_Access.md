Rules by Product and UseCase
============================
Vendor: QUSH
------------
### Product: [Reveal](../ds_qush_reveal.md)
### Use-Case: [Abnormal Authentication & Access](../../../../UseCases/uc_abnormal_authentication_&_access.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  42   |   24   |         6          |       4        |    1    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| nac-logon    | <b>T1021 - Remote Services</b><br> ↳ <b>NAC-OAt-F</b>: First authentication type for organization<br> ↳ <b>NAC-OAt-A</b>: Abnormal authentication type for organization<br> ↳ <b>NAC-GAt-F</b>: First authentication type for peer group<br> ↳ <b>NAC-GAt-A</b>: Abnormal authentication type for peer group<br> ↳ <b>NAC-UAt-F</b>: First authentication type for user<br> ↳ <b>NAC-UAt-A</b>: Abnormal authentication type for user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>DORMANT-USER</b>: Dormant User<br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>NAC-UAt-F</b>: First authentication type for user<br> ↳ <b>NAC-UAt-A</b>: Abnormal authentication type for user    |  • <b>NAC-UAt</b>: Authentication Types for user<br> • <b>NAC-GAt</b>: Authentication Types for peer group<br> • <b>NAC-OAt</b>: Authentication Types for organization<br> • <b>AE-UA</b>: All activity for users    |
| print-activity       | <b>T1078 - Valid Accounts</b><br> ↳ <b>DORMANT-USER</b>: Dormant User    |    |
| remote-logon         | <b>T1078 - Valid Accounts</b><br> ↳ <b>DORMANT-USER</b>: Dormant User<br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>AL-UT-F</b>: Logon to New Asset Type<br> ↳ <b>AL-UT-A</b>: Logon to Abnormal asset type<br> ↳ <b>AL-F-F-CS</b>: First logon to a critical system for user<br> ↳ <b>AL-F-A-CS</b>: Abnormal logon to a critical system for user<br> ↳ <b>AL-UH-CS-NC</b>: Logon to a critical system for a user with no information<br> ↳ <b>AL-OU-F-CS</b>: First logon to a critical system that user has not previously accessed<br> ↳ <b>RL-UH-F</b>: First remote logon to asset<br> ↳ <b>RL-UH-A</b>: Abnormal remote logon to asset<br> ↳ <b>AL-UZ-F</b>: First logon to network zone<br> ↳ <b>AL-UZ-A</b>: Abnormal logon to network zone<br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-GC-A</b>: Abnormal activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br> ↳ <b>UA-OC-A</b>: Abnormal activity from country for organization<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>NEW-USER-F</b>: User with no event history<br> ↳ <b>RL-GH-A-new</b>: Abnormal remote logon to asset for group by new user<br> ↳ <b>RL-GH-F-new</b>: First remote logon to asset for group by new user<br> ↳ <b>AL-GZ-F-new</b>: First logon to network zone for new user of group<br> ↳ <b>AL-GZ-A-new</b>: Abnormal logon to network zone for group of new user<br> ↳ <b>RL-HU-F-new</b>: Remote logon to private asset for new user<br> ↳ <b>PA-IT-NoPA</b>: IT presence without badge access<br><br><b>T1021 - Remote Services</b><br> ↳ <b>RL-UZ-F-DC</b>: First logon to a Domain Controller from zone for user<br> ↳ <b>RL-UH-F</b>: First remote logon to asset<br> ↳ <b>RL-UH-A</b>: Abnormal remote logon to asset<br> ↳ <b>RL-GH-A-new</b>: Abnormal remote logon to asset for group by new user<br> ↳ <b>RL-GH-F-new</b>: First remote logon to asset for group by new user<br> ↳ <b>RL-HU-F-new</b>: Remote logon to private asset for new user<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-F</b>: First activity from country for user<br> ↳ <b>UA-UC-A</b>: Abnormal activity from country for user<br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-GC-A</b>: Abnormal activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br> ↳ <b>UA-OC-A</b>: Abnormal activity from country for organization<br><br><b>T1078.002 - T1078.002</b><br> ↳ <b>RL-UZ-F-DC</b>: First logon to a Domain Controller from zone for user<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset<br> ↳ <b>AL-HLocU-A</b>: Abnormal local user logon to this asset |  • <b>PA-OU</b>: Badge access by users in the organization<br> • <b>RL-HU</b>: Remote logon users<br> • <b>AL-GZ</b>: Network zones accessed by this peer group<br> • <b>RL-GH-A</b>: Assets accessed remotely by this peer group<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer groups<br> • <b>UA-UC</b>: Countries for user activity<br> • <b>RL-UH</b>: Remote logons<br> • <b>RL-UZ-DC</b>: Source zones per user logging into domain controller<br> • <b>AL-OU-CS</b>: Logon to critical servers<br> • <b>RA-UH</b>: Assets accessed by this user remotely<br> • <b>AL-UT</b>: Types of hosts<br> • <b>AE-UA</b>: All activity for users<br> • <b>NKL-HU</b>: Users logging into this host remotely |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-UUa-OS-F</b>: First web activity using this operating system for this user<br> ↳ <b>WEB-UUa-MobileBrowser-F</b>: First activity using this mobile web browser/app for this user to a new domain<br> ↳ <b>WEB-OsUa-MobileBrowser-F</b>: First activity using this mobile web browser for this mobile operating system<br> ↳ <b>WEB-UT-TOW-A</b>: Abnormal day for this user to access the web via the organization<br> ↳ <b>WEB-UZ-F</b>: First web activity for this user in this zone<br> ↳ <b>WEB-GZ-F</b>: First web activity from this zone for the peer group<br> ↳ <b>WEB-OC-F</b>: First access to an internet IP address in this country for the organization    |  • <b>WEB-OC</b>: Web destination countries for org<br> • <b>WEB-GZ</b>: Network zones where users performs web activity in the peer group<br> • <b>WEB-UZ</b>: Network zones where a user performs web activity from<br> • <b>WEB-UT-TOW</b>: Web activity activity time for user<br> • <b>WEB-OsUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used in the organization for this type of device<br> • <b>WEB-UUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used by user<br> • <b>WEB-UUa-OS-New</b>: Top operating systems being used to connect to the web for user    |