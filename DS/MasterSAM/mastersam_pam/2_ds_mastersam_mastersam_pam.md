|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[ca-pamsc-kv-app-activity-admin](Ps/pC_capamsckvappactivityadmin.md)<br> ↳[ca-pamsc-kv-app-activity-sessionrecording-1](Ps/pC_capamsckvappactivitysessionrecording1.md)<br> ↳[ca-pamsc-kv-app-activity-system](Ps/pC_capamsckvappactivitysystem.md)<br> ↳[mastersam-pam-kv-app-activity-updateresource](Ps/pC_mastersampamkvappactivityupdateresource.md)<br> ↳[mastersam-pam-kv-app-activity-apiaccountrequest](Ps/pC_mastersampamkvappactivityapiaccountrequest.md)<br><br> authentication-successful<br> ↳[ca-pamsc-kv-app-authentication-connection](Ps/pC_capamsckvappauthenticationconnection.md)<br> ↳[mastersam-pam-kv-app-authentication-success-verifypasswordaccount](Ps/pC_mastersampamkvappauthenticationsuccessverifypasswordaccount.md)<br> ↳[mastersam-pam-kv-app-authentication-success-apilogin](Ps/pC_mastersampamkvappauthenticationsuccessapilogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-login](Ps/pC_mastersampamkvendpointauthenticationsuccesslogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-verifiedotp](Ps/pC_mastersampamkvendpointauthenticationsuccessverifiedotp.md)<br><br> database-login<br> ↳[apache-cassandradb-kv-database-login-success-auth](Ps/pC_apachecassandradbkvdatabaseloginsuccessauth.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1213 - Data from Information Repositories<br> | [<ul><li>49 Rules</li></ul><ul><li>29 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[ca-pamsc-kv-app-activity-admin](Ps/pC_capamsckvappactivityadmin.md)<br> ↳[ca-pamsc-kv-app-activity-sessionrecording-1](Ps/pC_capamsckvappactivitysessionrecording1.md)<br> ↳[ca-pamsc-kv-app-activity-system](Ps/pC_capamsckvappactivitysystem.md)<br> ↳[mastersam-pam-kv-app-activity-updateresource](Ps/pC_mastersampamkvappactivityupdateresource.md)<br> ↳[mastersam-pam-kv-app-activity-apiaccountrequest](Ps/pC_mastersampamkvappactivityapiaccountrequest.md)<br><br> database-login<br> ↳[apache-cassandradb-kv-database-login-success-auth](Ps/pC_apachecassandradbkvdatabaseloginsuccessauth.md)<br>    | T1078 - Valid Accounts<br>T1213 - Data from Information Repositories<br>    | [<ul><li>29 Rules</li></ul><ul><li>16 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Data_Access.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳[ca-pamsc-kv-app-activity-admin](Ps/pC_capamsckvappactivityadmin.md)<br> ↳[ca-pamsc-kv-app-activity-sessionrecording-1](Ps/pC_capamsckvappactivitysessionrecording1.md)<br> ↳[ca-pamsc-kv-app-activity-system](Ps/pC_capamsckvappactivitysystem.md)<br> ↳[mastersam-pam-kv-app-activity-updateresource](Ps/pC_mastersampamkvappactivityupdateresource.md)<br> ↳[mastersam-pam-kv-app-activity-apiaccountrequest](Ps/pC_mastersampamkvappactivityapiaccountrequest.md)<br><br> authentication-successful<br> ↳[ca-pamsc-kv-app-authentication-connection](Ps/pC_capamsckvappauthenticationconnection.md)<br> ↳[mastersam-pam-kv-app-authentication-success-verifypasswordaccount](Ps/pC_mastersampamkvappauthenticationsuccessverifypasswordaccount.md)<br> ↳[mastersam-pam-kv-app-authentication-success-apilogin](Ps/pC_mastersampamkvappauthenticationsuccessapilogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-login](Ps/pC_mastersampamkvendpointauthenticationsuccesslogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-verifiedotp](Ps/pC_mastersampamkvendpointauthenticationsuccessverifiedotp.md)<br>    | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_mastersam_mastersam_pam_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[ca-pamsc-kv-app-activity-admin](Ps/pC_capamsckvappactivityadmin.md)<br> ↳[ca-pamsc-kv-app-activity-sessionrecording-1](Ps/pC_capamsckvappactivitysessionrecording1.md)<br> ↳[ca-pamsc-kv-app-activity-system](Ps/pC_capamsckvappactivitysystem.md)<br> ↳[mastersam-pam-kv-app-activity-updateresource](Ps/pC_mastersampamkvappactivityupdateresource.md)<br> ↳[mastersam-pam-kv-app-activity-apiaccountrequest](Ps/pC_mastersampamkvappactivityapiaccountrequest.md)<br><br> authentication-successful<br> ↳[ca-pamsc-kv-app-authentication-connection](Ps/pC_capamsckvappauthenticationconnection.md)<br> ↳[mastersam-pam-kv-app-authentication-success-verifypasswordaccount](Ps/pC_mastersampamkvappauthenticationsuccessverifypasswordaccount.md)<br> ↳[mastersam-pam-kv-app-authentication-success-apilogin](Ps/pC_mastersampamkvappauthenticationsuccessapilogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-login](Ps/pC_mastersampamkvendpointauthenticationsuccesslogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-verifiedotp](Ps/pC_mastersampamkvendpointauthenticationsuccessverifiedotp.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_mastersam_mastersam_pam_Malware.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[ca-pamsc-kv-app-activity-admin](Ps/pC_capamsckvappactivityadmin.md)<br> ↳[ca-pamsc-kv-app-activity-sessionrecording-1](Ps/pC_capamsckvappactivitysessionrecording1.md)<br> ↳[ca-pamsc-kv-app-activity-system](Ps/pC_capamsckvappactivitysystem.md)<br> ↳[mastersam-pam-kv-app-activity-updateresource](Ps/pC_mastersampamkvappactivityupdateresource.md)<br> ↳[mastersam-pam-kv-app-activity-apiaccountrequest](Ps/pC_mastersampamkvappactivityapiaccountrequest.md)<br><br> authentication-successful<br> ↳[ca-pamsc-kv-app-authentication-connection](Ps/pC_capamsckvappauthenticationconnection.md)<br> ↳[mastersam-pam-kv-app-authentication-success-verifypasswordaccount](Ps/pC_mastersampamkvappauthenticationsuccessverifypasswordaccount.md)<br> ↳[mastersam-pam-kv-app-authentication-success-apilogin](Ps/pC_mastersampamkvappauthenticationsuccessapilogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-login](Ps/pC_mastersampamkvendpointauthenticationsuccesslogin.md)<br> ↳[mastersam-pam-kv-endpoint-authentication-success-verifiedotp](Ps/pC_mastersampamkvendpointauthenticationsuccessverifiedotp.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_mastersam_mastersam_pam_Ransomware.md)    |