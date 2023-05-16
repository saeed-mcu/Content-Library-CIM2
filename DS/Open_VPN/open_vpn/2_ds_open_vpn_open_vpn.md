|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-login<br> ↳[openvpn-ov-json-vpn-login-success-connection](Ps/pC_openvpnovjsonvpnloginsuccessconnection.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br> | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>57 Rules</li></ul><ul><li>32 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br>    | T1078 - Valid Accounts<br>T1110 - Brute Force<br>    | [<ul><li>20 Rules</li></ul><ul><li>12 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1114.003 - Email Collection: Email Forwarding Rule<br>T1133 - External Remote Services<br>TA0010 - TA0010<br> | [<ul><li>14 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Data_Leak.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-login<br> ↳[openvpn-ov-json-vpn-login-success-connection](Ps/pC_openvpnovjsonvpnloginsuccessconnection.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>    | [<ul><li>8 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Lateral_Movement.md)          |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-login<br> ↳[openvpn-ov-json-vpn-login-success-connection](Ps/pC_openvpnovjsonvpnloginsuccessconnection.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br>    | [<ul><li>9 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[openvpn-ov-str-app-activity-datachannel](Ps/pC_openvpnovstrappactivitydatachannel.md)<br><br> vpn-logout<br> ↳[openvpn-ov-str-vpn-logout-success-reset-1](Ps/pC_openvpnovstrvpnlogoutsuccessreset1.md)<br> ↳[openvpn-ov-str-vpn-logout-success-reset](Ps/pC_openvpnovstrvpnlogoutsuccessreset.md)<br> ↳[openvpn-ov-str-vpn-logout-success-timeout](Ps/pC_openvpnovstrvpnlogoutsuccesstimeout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-loggedout](Ps/pC_sslopenvpnskvvpnlogoutsuccessloggedout.md)<br> ↳[sslopenvpn-s-kv-vpn-logout-success-terminated](Ps/pC_sslopenvpnskvvpnlogoutsuccessterminated.md)<br>    | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1555.005 - T1555.005<br>    | [<ul><li>8 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_open_vpn_open_vpn_Privilege_Escalation.md)      |