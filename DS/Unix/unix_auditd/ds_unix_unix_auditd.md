Vendor: Unix
============
Product: Unix Auditd
--------------------
| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  642  |  114   |        130         |       12       |   12    |

|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-creation<br> ↳[unix-auditd-kv-user-create-success-addgroup](Ps/pC_unixauditdkvusercreatesuccessaddgroup.md)<br> ↳[unix-auditd-kv-user-create-success-adduser](Ps/pC_unixauditdkvusercreatesuccessadduser.md)<br><br> account-deleted<br> ↳[unix-auditd-kv-user-delete-success-deleteuser](Ps/pC_unixauditdkvuserdeletesuccessdeleteuser.md)<br><br> account-password-change<br> ↳[unix-unixauditd-kv-user-password-modify-success-grpmgmt](Ps/pC_unixunixauditdkvuserpasswordmodifysuccessgrpmgmt.md)<br><br> account-switch<br> ↳[unix-unix-cef-user-switch-success-sessionclose](Ps/pC_unixunixcefuserswitchsuccesssessionclose.md)<br> ↳[unix-unix-json-user-switch-success-process](Ps/pC_unixunixjsonuserswitchsuccessprocess.md)<br> ↳[unix-unix-cef-user-switch-success-susuccess](Ps/pC_unixunixcefuserswitchsuccesssusuccess.md)<br> ↳[unix-auditd-kv-user-switch-success-sessionopen](Ps/pC_unixauditdkvuserswitchsuccesssessionopen.md)<br> ↳[unix-auditd-kv-user-switch-success-userrolechange](Ps/pC_unixauditdkvuserswitchsuccessuserrolechange.md)<br><br> app-activity<br> ↳[unix-ad-cef-app-activity-unix](Ps/pC_unixadcefappactivityunix.md)<br><br> authentication-successful<br> ↳[unix-ad-cef-endpoint-login-success-userauth](Ps/pC_unixadcefendpointloginsuccessuserauth.md)<br> ↳[unix-unix-cef-endpoint-login-success-sessionstart](Ps/pC_unixunixcefendpointloginsuccesssessionstart.md)<br> ↳[unix-ad-cef-authentication-success-credacq](Ps/pC_unixadcefauthenticationsuccesscredacq.md)<br> ↳[unix-ad-kv-endpoint-authentication-credrefr](Ps/pC_unixadkvendpointauthenticationcredrefr.md)<br> ↳[unix-unix-sk4-endpoint-authentication-useracct](Ps/pC_unixunixsk4endpointauthenticationuseracct.md)<br> ↳[unix-unix-sk4-endpoint-authentication-credacq](Ps/pC_unixunixsk4endpointauthenticationcredacq.md)<br> ↳[unix-unix-sk4-endpoint-authentication-credrefr](Ps/pC_unixunixsk4endpointauthenticationcredrefr.md)<br> ↳[unix-ad-cef-endpoint-authentication-credrefr](Ps/pC_unixadcefendpointauthenticationcredrefr.md)<br> ↳[unix-ad-kv-endpoint-authentication-accounting](Ps/pC_unixadkvendpointauthenticationaccounting.md)<br> ↳[unix-ad-kv-endpoint-authentication-creddisp](Ps/pC_unixadkvendpointauthenticationcreddisp.md)<br> ↳[unix-ad-kv-endpoint-authentication-credacq](Ps/pC_unixadkvendpointauthenticationcredacq.md)<br> ↳[unix-ad-cef-endpoint-authentication-success-creddisp](Ps/pC_unixadcefendpointauthenticationsuccesscreddisp.md)<br> ↳[unix-unix-sk4-endpoint-authentication-creddisp](Ps/pC_unixunixsk4endpointauthenticationcreddisp.md)<br><br> failed-logon<br> ↳[unix-ad-cef-endpoint-login-fail-failedlogin](Ps/pC_unixadcefendpointloginfailfailedlogin.md)<br> | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>17 Rules</li></ul><ul><li>6 Models</li></ul>](RM/r_m_unix_unix_auditd_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  account-creation<br> ↳[unix-auditd-kv-user-create-success-addgroup](Ps/pC_unixauditdkvusercreatesuccessaddgroup.md)<br> ↳[unix-auditd-kv-user-create-success-adduser](Ps/pC_unixauditdkvusercreatesuccessadduser.md)<br><br> account-deleted<br> ↳[unix-auditd-kv-user-delete-success-deleteuser](Ps/pC_unixauditdkvuserdeletesuccessdeleteuser.md)<br><br> account-password-change<br> ↳[unix-unixauditd-kv-user-password-modify-success-grpmgmt](Ps/pC_unixunixauditdkvuserpasswordmodifysuccessgrpmgmt.md)<br><br> app-activity<br> ↳[unix-ad-cef-app-activity-unix](Ps/pC_unixadcefappactivityunix.md)<br><br> process-created<br> ↳[unix-ad-kv-process-create-success-audit](Ps/pC_unixadkvprocesscreatesuccessaudit.md)<br> ↳[unix-ad-kv-process-create-success-audispd](Ps/pC_unixadkvprocesscreatesuccessaudispd.md)<br> ↳[unix-ad-cef-process-create-success-cmd](Ps/pC_unixadcefprocesscreatesuccesscmd.md)<br> ↳[unix-unixauditd-cef-process-create-success-execve](Ps/pC_unixunixauditdcefprocesscreatesuccessexecve.md)<br> ↳[unix-unixauditd-cef-process-create-success-syscall](Ps/pC_unixunixauditdcefprocesscreatesuccesssyscall.md)<br> ↳[unix-unixauditd-cef-process-create-success-usercmd](Ps/pC_unixunixauditdcefprocesscreatesuccessusercmd.md)<br>    | T1003 - OS Credential Dumping<br>T1003.003 - T1003.003<br>T1021.003 - T1021.003<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1059.003 - T1059.003<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1136 - Create Account<br>T1136.001 - Create Account: Create: Local Account<br>T1136.002 - T1136.002<br>T1218.010 - Signed Binary Proxy Execution: Regsvr32<br>T1531 - Account Access Removal<br>T1559.002 - T1559.002<br> | [<ul><li>40 Rules</li></ul><ul><li>15 Models</li></ul>](RM/r_m_unix_unix_auditd_Account_Manipulation.md)    |
|    [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)    |  failed-logon<br> ↳[unix-ad-cef-endpoint-login-fail-failedlogin](Ps/pC_unixadcefendpointloginfailfailedlogin.md)<br>    | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1110 - Brute Force<br>T1110.003 - T1110.003<br>    | [<ul><li>9 Rules</li></ul>](RM/r_m_unix_unix_auditd_Brute_Force_Attack.md)    |
[Next Page -->>](2_ds_unix_unix_auditd.md)

MITRE ATT&CK® Framework for Enterprise
--------------------------------------
| Initial Access                                                                                                                                                                                                                                                                                      | Execution                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Persistence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Privilege Escalation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Credential Access                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Discovery                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Lateral Movement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Collection                                                                                                                                                                                                                                                                                                                                                                            | Command and Control                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Exfiltration                                                                                                                                                                                                                                            | Impact                                                                                                                                                                                                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br>[Phishing](https://attack.mitre.org/techniques/T1566)<br><br> | [Windows Management Instrumentation](https://attack.mitre.org/techniques/T1047)<br><br>[Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br>[Inter-Process Communication](https://attack.mitre.org/techniques/T1559)<br><br>[System Services](https://attack.mitre.org/techniques/T1569)<br><br>[Exploitation for Client Execution](https://attack.mitre.org/techniques/T1203)<br><br>[User Execution](https://attack.mitre.org/techniques/T1204)<br><br>[Scheduled Task/Job: Scheduled Task](https://attack.mitre.org/techniques/T1053/005)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br>[Scheduled Task/Job: At (Windows)](https://attack.mitre.org/techniques/T1053/002)<br><br> | [Pre-OS Boot](https://attack.mitre.org/techniques/T1542)<br><br>[Create Account](https://attack.mitre.org/techniques/T1136)<br><br>[Create or Modify System Process](https://attack.mitre.org/techniques/T1543)<br><br>[External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br>[Server Software Component: Web Shell](https://attack.mitre.org/techniques/T1505/003)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[BITS Jobs](https://attack.mitre.org/techniques/T1197)<br><br>[Create or Modify System Process: Windows Service](https://attack.mitre.org/techniques/T1543/003)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br>[Server Software Component](https://attack.mitre.org/techniques/T1505)<br><br>[Event Triggered Execution](https://attack.mitre.org/techniques/T1546)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br>[Create Account: Create: Local Account](https://attack.mitre.org/techniques/T1136/001)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Access Token Manipulation: Token Impersonation/Theft](https://attack.mitre.org/techniques/T1134/001)<br><br>[Create or Modify System Process](https://attack.mitre.org/techniques/T1543)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Access Token Manipulation](https://attack.mitre.org/techniques/T1134)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br>[Group Policy Modification](https://attack.mitre.org/techniques/T1484)<br><br>[Process Injection](https://attack.mitre.org/techniques/T1055)<br><br>[Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)<br><br>[Abuse Elevation Control Mechanism](https://attack.mitre.org/techniques/T1548)<br><br>[Event Triggered Execution](https://attack.mitre.org/techniques/T1546)<br><br>[Boot or Logon Autostart Execution](https://attack.mitre.org/techniques/T1547)<br><br>[Process Injection: Dynamic-link Library Injection](https://attack.mitre.org/techniques/T1055/001)<br><br>[Abuse Elevation Control Mechanism: Bypass User Account Control](https://attack.mitre.org/techniques/T1548/002)<br><br> | [Hide Artifacts](https://attack.mitre.org/techniques/T1564)<br><br>[Indirect Command Execution](https://attack.mitre.org/techniques/T1202)<br><br>[Impair Defenses](https://attack.mitre.org/techniques/T1562)<br><br>[Indicator Removal on Host: Clear Windows Event Logs](https://attack.mitre.org/techniques/T1070/001)<br><br>[Group Policy Modification](https://attack.mitre.org/techniques/T1484)<br><br>[Trusted Developer Utilities Proxy Execution](https://attack.mitre.org/techniques/T1127)<br><br>[Masquerading: Match Legitimate Name or Location](https://attack.mitre.org/techniques/T1036/005)<br><br>[Masquerading: Rename System Utilities](https://attack.mitre.org/techniques/T1036/003)<br><br>[File and Directory Permissions Modification: Windows File and Directory Permissions Modification](https://attack.mitre.org/techniques/T1222/001)<br><br>[Obfuscated Files or Information: Compile After Delivery](https://attack.mitre.org/techniques/T1027/004)<br><br>[Hijack Execution Flow: DLL Side-Loading](https://attack.mitre.org/techniques/T1574/002)<br><br>[Masquerading](https://attack.mitre.org/techniques/T1036)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Modify Registry](https://attack.mitre.org/techniques/T1112)<br><br>[BITS Jobs](https://attack.mitre.org/techniques/T1197)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Hide Artifacts: NTFS File Attributes](https://attack.mitre.org/techniques/T1564/004)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Indicator Removal on Host](https://attack.mitre.org/techniques/T1070)<br><br>[Use Alternate Authentication Material: Pass the Ticket](https://attack.mitre.org/techniques/T1550/003)<br><br>[Pre-OS Boot](https://attack.mitre.org/techniques/T1542)<br><br>[File and Directory Permissions Modification](https://attack.mitre.org/techniques/T1222)<br><br>[Deobfuscate/Decode Files or Information](https://attack.mitre.org/techniques/T1140)<br><br>[Abuse Elevation Control Mechanism](https://attack.mitre.org/techniques/T1548)<br><br>[Impair Defenses: Disable or Modify System Firewall](https://attack.mitre.org/techniques/T1562/004)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br>[Signed Binary Proxy Execution: Compiled HTML File](https://attack.mitre.org/techniques/T1218/001)<br><br>[Access Token Manipulation](https://attack.mitre.org/techniques/T1134)<br><br>[Hijack Execution Flow](https://attack.mitre.org/techniques/T1574)<br><br>[Process Injection](https://attack.mitre.org/techniques/T1055)<br><br>[Signed Binary Proxy Execution: Msiexec](https://attack.mitre.org/techniques/T1218/007)<br><br>[Signed Binary Proxy Execution](https://attack.mitre.org/techniques/T1218)<br><br>[Signed Binary Proxy Execution: Regsvcs/Regasm](https://attack.mitre.org/techniques/T1218/009)<br><br>[Signed Binary Proxy Execution: CMSTP](https://attack.mitre.org/techniques/T1218/003)<br><br>[Signed Binary Proxy Execution: Control Panel](https://attack.mitre.org/techniques/T1218/002)<br><br>[Signed Binary Proxy Execution: InstallUtil](https://attack.mitre.org/techniques/T1218/004)<br><br>[Signed Binary Proxy Execution: Regsvr32](https://attack.mitre.org/techniques/T1218/010)<br><br>[Trusted Developer Utilities Proxy Execution: MSBuild](https://attack.mitre.org/techniques/T1127/001)<br><br>[Signed Binary Proxy Execution: Rundll32](https://attack.mitre.org/techniques/T1218/011)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br>[Unsecured Credentials](https://attack.mitre.org/techniques/T1552)<br><br>[Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br>[Credentials from Password Stores](https://attack.mitre.org/techniques/T1555)<br><br>[Steal or Forge Kerberos Tickets: Kerberoasting](https://attack.mitre.org/techniques/T1558/003)<br><br>[Network Sniffing](https://attack.mitre.org/techniques/T1040)<br><br> | [Account Discovery](https://attack.mitre.org/techniques/T1087)<br><br>[Domain Trust Discovery](https://attack.mitre.org/techniques/T1482)<br><br>[System Service Discovery](https://attack.mitre.org/techniques/T1007)<br><br>[System Network Connections Discovery](https://attack.mitre.org/techniques/T1049)<br><br>[Account Discovery: Local Account](https://attack.mitre.org/techniques/T1087/001)<br><br>[Account Discovery: Domain Account](https://attack.mitre.org/techniques/T1087/002)<br><br>[File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br>[Network Sniffing](https://attack.mitre.org/techniques/T1040)<br><br>[System Information Discovery](https://attack.mitre.org/techniques/T1082)<br><br>[Network Share Discovery](https://attack.mitre.org/techniques/T1135)<br><br>[Query Registry](https://attack.mitre.org/techniques/T1012)<br><br>[Process Discovery](https://attack.mitre.org/techniques/T1057)<br><br>[System Owner/User Discovery](https://attack.mitre.org/techniques/T1033)<br><br>[Software Discovery](https://attack.mitre.org/techniques/T1518)<br><br>[Remote System Discovery](https://attack.mitre.org/techniques/T1018)<br><br>[System Network Configuration Discovery](https://attack.mitre.org/techniques/T1016)<br><br> | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Service Session Hijacking](https://attack.mitre.org/techniques/T1563)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Remote Services: SMB/Windows Admin Shares](https://attack.mitre.org/techniques/T1021/002)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> | [Screen Capture](https://attack.mitre.org/techniques/T1113)<br><br>[Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Audio Capture](https://attack.mitre.org/techniques/T1123)<br><br>[Archive Collected Data](https://attack.mitre.org/techniques/T1560)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Protocol Tunneling](https://attack.mitre.org/techniques/T1572)<br><br>[Application Layer Protocol: DNS](https://attack.mitre.org/techniques/T1071/004)<br><br>[Application Layer Protocol: File Transfer Protocols](https://attack.mitre.org/techniques/T1071/002)<br><br>[Application Layer Protocol: Web Protocols](https://attack.mitre.org/techniques/T1071/001)<br><br>[Remote Access Software](https://attack.mitre.org/techniques/T1219)<br><br>[Ingress Tool Transfer](https://attack.mitre.org/techniques/T1105)<br><br>[Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over C2 Channel](https://attack.mitre.org/techniques/T1041)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> | [Account Access Removal](https://attack.mitre.org/techniques/T1531)<br><br>[Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br>[Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486)<br><br>[Inhibit System Recovery](https://attack.mitre.org/techniques/T1490)<br><br> |