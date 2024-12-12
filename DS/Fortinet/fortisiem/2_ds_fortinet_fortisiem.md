|    Use-Case    | Activity Type (Legacy Event Type)/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
|    [Malware](../../../UseCases/uc_malware.md)    |  endpoint-login:success (authentication-successful)<br> ↳[fortinet-fortisiem-kv-endpoint-login-kevent](Ps/pC_fortinetfortisiemkvendpointloginkevent.md)<br><br> email-receive:success (dlp-email-alert-in)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-send:success (dlp-email-alert-out)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> alert-trigger:success (security-alert)<br> ↳[fortinet-fortisiem-kv-alert-trigger-success](Ps/pC_fortinetfortisiemkvalerttriggersuccess.md)<br>    | T1078 - Valid Accounts<br>T1190 - Exploit Public Fasing Application<br>TA0002 - TA0002<br> | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fortinet_fortisiem_Malware.md) |
|     [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)     |  email-receive:success (dlp-email-alert-in)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-receive:fail (dlp-email-alert-in-failed)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-send:success (dlp-email-alert-out)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-send:fail (dlp-email-alert-out-failed)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_fortinet_fortisiem_Privilege_Abuse.md)    |
| [Privileged Activity](../../../UseCases/uc_privileged_activity.md) |  email-receive:success (dlp-email-alert-in)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-receive:fail (dlp-email-alert-in-failed)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-send:success (dlp-email-alert-out)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> email-send:fail (dlp-email-alert-out-failed)<br> ↳[fortinet-fortisiem-kv-email-statistics](Ps/pC_fortinetfortisiemkvemailstatistics.md)<br><br> alert-trigger:success (security-alert)<br> ↳[fortinet-fortisiem-kv-alert-trigger-success](Ps/pC_fortinetfortisiemkvalerttriggersuccess.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_fortinet_fortisiem_Privileged_Activity.md)    |