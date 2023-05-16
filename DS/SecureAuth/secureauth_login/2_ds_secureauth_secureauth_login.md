|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br><br> authentication-successful<br> ↳[secureauth-login-xml-app-authentication-browserfingerprint](Ps/pC_secureauthloginxmlappauthenticationbrowserfingerprint.md)<br> ↳[secureauth-login-kv-app-authentication-51170](Ps/pC_secureauthloginkvappauthentication51170.md)<br> ↳[secureauth-login-kv-app-authentication-24120](Ps/pC_secureauthloginkvappauthentication24120.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22600](Ps/pC_secureauthloginkvappauthenticationfail22600.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1190 - Exploit Public Fasing Application<br> | [<ul><li>42 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_secureauth_secureauth_login_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_secureauth_secureauth_login_Data_Access.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br><br> authentication-failed<br> ↳[secureauth-login-kv-app-authentication-fail-22610](Ps/pC_secureauthloginkvappauthenticationfail22610.md)<br> ↳[secureauth-login-kv-app-authentication-fail-51150](Ps/pC_secureauthloginkvappauthenticationfail51150.md)<br> ↳[secureauth-login-kv-app-authentication-fail-41501-1](Ps/pC_secureauthloginkvappauthenticationfail415011.md)<br> ↳[secureauth-login-kv-app-authentication-fail-41501](Ps/pC_secureauthloginkvappauthenticationfail41501.md)<br> ↳[secureauth-login-kv-app-authentication-fail-24220](Ps/pC_secureauthloginkvappauthenticationfail24220.md)<br> ↳[secureauth-login-kv-app-authentication-fail-24210](Ps/pC_secureauthloginkvappauthenticationfail24210.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22910](Ps/pC_secureauthloginkvappauthenticationfail22910.md)<br><br> authentication-successful<br> ↳[secureauth-login-xml-app-authentication-browserfingerprint](Ps/pC_secureauthloginxmlappauthenticationbrowserfingerprint.md)<br> ↳[secureauth-login-kv-app-authentication-51170](Ps/pC_secureauthloginkvappauthentication51170.md)<br> ↳[secureauth-login-kv-app-authentication-24120](Ps/pC_secureauthloginkvappauthentication24120.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22600](Ps/pC_secureauthloginkvappauthenticationfail22600.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_secureauth_secureauth_login_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br><br> authentication-successful<br> ↳[secureauth-login-xml-app-authentication-browserfingerprint](Ps/pC_secureauthloginxmlappauthenticationbrowserfingerprint.md)<br> ↳[secureauth-login-kv-app-authentication-51170](Ps/pC_secureauthloginkvappauthentication51170.md)<br> ↳[secureauth-login-kv-app-authentication-24120](Ps/pC_secureauthloginkvappauthentication24120.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22600](Ps/pC_secureauthloginkvappauthenticationfail22600.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_secureauth_secureauth_login_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br>    | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>         | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_secureauth_secureauth_login_Privilege_Abuse.md)    |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_secureauth_secureauth_login_Privileged_Activity.md)       |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[secureauth-login-kv-http-request-41690](Ps/pC_secureauthloginkvhttprequest41690.md)<br> ↳[secureauth-login-cef-app-activity-appactivity](Ps/pC_secureauthlogincefappactivityappactivity.md)<br> ↳[secureauth-login-leef-app-activity](Ps/pC_secureauthloginleefappactivity.md)<br><br> app-login<br> ↳[secureauth-login-kv-app-login-90010](Ps/pC_secureauthloginkvapplogin90010.md)<br> ↳[secureauth-login-xml-app-login-success-priority](Ps/pC_secureauthloginxmlapploginsuccesspriority.md)<br><br> authentication-failed<br> ↳[secureauth-login-kv-app-authentication-fail-22610](Ps/pC_secureauthloginkvappauthenticationfail22610.md)<br> ↳[secureauth-login-kv-app-authentication-fail-51150](Ps/pC_secureauthloginkvappauthenticationfail51150.md)<br> ↳[secureauth-login-kv-app-authentication-fail-41501-1](Ps/pC_secureauthloginkvappauthenticationfail415011.md)<br> ↳[secureauth-login-kv-app-authentication-fail-41501](Ps/pC_secureauthloginkvappauthenticationfail41501.md)<br> ↳[secureauth-login-kv-app-authentication-fail-24220](Ps/pC_secureauthloginkvappauthenticationfail24220.md)<br> ↳[secureauth-login-kv-app-authentication-fail-24210](Ps/pC_secureauthloginkvappauthenticationfail24210.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22910](Ps/pC_secureauthloginkvappauthenticationfail22910.md)<br><br> authentication-successful<br> ↳[secureauth-login-xml-app-authentication-browserfingerprint](Ps/pC_secureauthloginxmlappauthenticationbrowserfingerprint.md)<br> ↳[secureauth-login-kv-app-authentication-51170](Ps/pC_secureauthloginkvappauthentication51170.md)<br> ↳[secureauth-login-kv-app-authentication-24120](Ps/pC_secureauthloginkvappauthentication24120.md)<br> ↳[secureauth-login-kv-app-authentication-fail-22600](Ps/pC_secureauthloginkvappauthenticationfail22600.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_secureauth_secureauth_login_Ransomware.md)    |