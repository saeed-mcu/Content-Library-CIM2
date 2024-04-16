|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br> | [<ul><li>46 Rules</li></ul><ul><li>26 Models</li></ul>](RM/r_m_workday_workday_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>23 Rules</li></ul><ul><li>13 Models</li></ul>](RM/r_m_workday_workday_Data_Access.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> authentication-failed<br> ↳[workday-wd-cef-endpoint-login-fail-proxyusername](Ps/pC_workdaywdcefendpointloginfailproxyusername.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_workday_workday_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> authentication-failed<br> ↳[workday-wd-cef-endpoint-login-fail-proxyusername](Ps/pC_workdaywdcefendpointloginfailproxyusername.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_workday_workday_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br>    | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>         | [<ul><li>7 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_workday_workday_Privilege_Abuse.md)    |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_workday_workday_Privileged_Activity.md)       |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[workday-wd-json-app-activity-success-activityaction](Ps/pC_workdaywdjsonappactivitysuccessactivityaction.md)<br> ↳[workday-wd-json-app-activity-success-appactivity](Ps/pC_workdaywdjsonappactivitysuccessappactivity.md)<br><br> app-login<br> ↳[workday-wd-cef-app-login-success-authentication](Ps/pC_workdaywdcefapploginsuccessauthentication.md)<br> ↳[workday-wd-json-app-login-success-startnewsession-1](Ps/pC_workdaywdjsonapploginsuccessstartnewsession1.md)<br> ↳[workday-wd-json-app-login-success-startnewsession](Ps/pC_workdaywdjsonapploginsuccessstartnewsession.md)<br><br> authentication-failed<br> ↳[workday-wd-cef-endpoint-login-fail-proxyusername](Ps/pC_workdaywdcefendpointloginfailproxyusername.md)<br><br> failed-app-login<br> ↳[workday-wd-cef-app-login-fail-expired](Ps/pC_workdaywdcefapploginfailexpired.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_workday_workday_Ransomware.md)    |