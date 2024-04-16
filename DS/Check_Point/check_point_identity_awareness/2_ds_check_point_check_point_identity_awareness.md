|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  network-alert<br> ↳[checkpoint-ia-kv-alert-trigger-success-attack](Ps/pC_checkpointiakvalerttriggersuccessattack.md)<br> ↳[checkpoint-ia-kv-alert-trigger-success-attack](Ps/pC_checkpointiakvalerttriggersuccessattack.md)<br><br> vpn-login<br> ↳[checkpoint-ia-kv-vpn-login-success-successfullogin](Ps/pC_checkpointiakvvpnloginsuccesssuccessfullogin.md)<br> ↳[checkpoint-ia-kv-vpn-login-success-login](Ps/pC_checkpointiakvvpnloginsuccesslogin.md)<br><br> vpn-logout<br> ↳[checkpoint-ia-kv-vpn-logout-success-awareness](Ps/pC_checkpointiakvvpnlogoutsuccessawareness.md)<br> ↳[checkpoint-ia-kv-vpn-logout-success-logout](Ps/pC_checkpointiakvvpnlogoutsuccesslogout.md)<br>    | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br>    | [<ul><li>50 Rules</li></ul><ul><li>22 Models</li></ul>](RM/r_m_check_point_check_point_identity_awareness_Compromised_Credentials.md) |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  network-connection-failed<br> ↳[checkpoint-ia-kv-network-traffic-firewall](Ps/pC_checkpointiakvnetworktrafficfirewall.md)<br><br> network-connection-successful<br> ↳[checkpoint-ia-kv-network-traffic-firewall](Ps/pC_checkpointiakvnetworktrafficfirewall.md)<br><br> vpn-login<br> ↳[checkpoint-ia-kv-vpn-login-success-successfullogin](Ps/pC_checkpointiakvvpnloginsuccesssuccessfullogin.md)<br> ↳[checkpoint-ia-kv-vpn-login-success-login](Ps/pC_checkpointiakvvpnloginsuccesslogin.md)<br><br> vpn-logout<br> ↳[checkpoint-ia-kv-vpn-logout-success-awareness](Ps/pC_checkpointiakvvpnlogoutsuccessawareness.md)<br> ↳[checkpoint-ia-kv-vpn-logout-success-logout](Ps/pC_checkpointiakvvpnlogoutsuccesslogout.md)<br>          | T1021 - Remote Services<br>T1048 - Exfiltration Over Alternative Protocol<br>T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1190 - Exploit Public Fasing Application<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>TA0010 - TA0010<br>TA0011 - TA0011<br> | [<ul><li>80 Rules</li></ul><ul><li>27 Models</li></ul>](RM/r_m_check_point_check_point_identity_awareness_Lateral_Movement.md)        |
|    [Malware](../../../UseCases/uc_malware.md)    |  network-alert<br> ↳[checkpoint-ia-kv-alert-trigger-success-attack](Ps/pC_checkpointiakvalerttriggersuccessattack.md)<br> ↳[checkpoint-ia-kv-alert-trigger-success-attack](Ps/pC_checkpointiakvalerttriggersuccessattack.md)<br><br> network-connection-failed<br> ↳[checkpoint-ia-kv-network-traffic-firewall](Ps/pC_checkpointiakvnetworktrafficfirewall.md)<br><br> network-connection-successful<br> ↳[checkpoint-ia-kv-network-traffic-firewall](Ps/pC_checkpointiakvnetworktrafficfirewall.md)<br><br> vpn-login<br> ↳[checkpoint-ia-kv-vpn-login-success-successfullogin](Ps/pC_checkpointiakvvpnloginsuccesssuccessfullogin.md)<br> ↳[checkpoint-ia-kv-vpn-login-success-login](Ps/pC_checkpointiakvvpnloginsuccesslogin.md)<br> | T1078 - Valid Accounts<br>TA0002 - TA0002<br>TA0011 - TA0011<br>    | [<ul><li>11 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_check_point_check_point_identity_awareness_Malware.md)    |