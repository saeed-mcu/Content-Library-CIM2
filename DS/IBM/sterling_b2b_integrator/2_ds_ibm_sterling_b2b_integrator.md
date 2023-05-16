|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[ibm-sbi-str-app-activity-systemname](Ps/pC_ibmsbistrappactivitysystemname.md)<br> ↳[ibm-sbi-csv-app-activity-runtimestate](Ps/pC_ibmsbicsvappactivityruntimestate.md)<br> ↳[ibm-sbi-csv-app-activity-removejndi](Ps/pC_ibmsbicsvappactivityremovejndi.md)<br> ↳[ibm-sbi-csv-service-stop-stateless](Ps/pC_ibmsbicsvservicestopstateless.md)<br> ↳[ibm-sbi-csv-service-stop-softstop](Ps/pC_ibmsbicsvservicestopsoftstop.md)<br><br> authentication-successful<br> ↳[ibm-sbi-str-app-authentication-success-authenticationpolicy](Ps/pC_ibmsbistrappauthenticationsuccessauthenticationpolicy.md)<br>    | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | [<ul><li>39 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_ibm_sterling_b2b_integrator_Compromised_Credentials.md) |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳[ibm-sbi-str-app-activity-systemname](Ps/pC_ibmsbistrappactivitysystemname.md)<br> ↳[ibm-sbi-csv-app-activity-runtimestate](Ps/pC_ibmsbicsvappactivityruntimestate.md)<br> ↳[ibm-sbi-csv-app-activity-removejndi](Ps/pC_ibmsbicsvappactivityremovejndi.md)<br> ↳[ibm-sbi-csv-service-stop-stateless](Ps/pC_ibmsbicsvservicestopstateless.md)<br> ↳[ibm-sbi-csv-service-stop-softstop](Ps/pC_ibmsbicsvservicestopsoftstop.md)<br><br> authentication-failed<br> ↳[ibm-sbi-str-app-authentication-fail-authorizationfailed](Ps/pC_ibmsbistrappauthenticationfailauthorizationfailed.md)<br><br> authentication-successful<br> ↳[ibm-sbi-str-app-authentication-success-authenticationpolicy](Ps/pC_ibmsbistrappauthenticationsuccessauthenticationpolicy.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>2 Rules</li></ul>](RM/r_m_ibm_sterling_b2b_integrator_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[ibm-sbi-str-app-activity-systemname](Ps/pC_ibmsbistrappactivitysystemname.md)<br> ↳[ibm-sbi-csv-app-activity-runtimestate](Ps/pC_ibmsbicsvappactivityruntimestate.md)<br> ↳[ibm-sbi-csv-app-activity-removejndi](Ps/pC_ibmsbicsvappactivityremovejndi.md)<br> ↳[ibm-sbi-csv-service-stop-stateless](Ps/pC_ibmsbicsvservicestopstateless.md)<br> ↳[ibm-sbi-csv-service-stop-softstop](Ps/pC_ibmsbicsvservicestopsoftstop.md)<br><br> authentication-successful<br> ↳[ibm-sbi-str-app-authentication-success-authenticationpolicy](Ps/pC_ibmsbistrappauthenticationsuccessauthenticationpolicy.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_ibm_sterling_b2b_integrator_Malware.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[ibm-sbi-str-app-activity-systemname](Ps/pC_ibmsbistrappactivitysystemname.md)<br> ↳[ibm-sbi-csv-app-activity-runtimestate](Ps/pC_ibmsbicsvappactivityruntimestate.md)<br> ↳[ibm-sbi-csv-app-activity-removejndi](Ps/pC_ibmsbicsvappactivityremovejndi.md)<br> ↳[ibm-sbi-csv-service-stop-stateless](Ps/pC_ibmsbicsvservicestopstateless.md)<br> ↳[ibm-sbi-csv-service-stop-softstop](Ps/pC_ibmsbicsvservicestopsoftstop.md)<br><br> authentication-failed<br> ↳[ibm-sbi-str-app-authentication-fail-authorizationfailed](Ps/pC_ibmsbistrappauthenticationfailauthorizationfailed.md)<br><br> authentication-successful<br> ↳[ibm-sbi-str-app-authentication-success-authenticationpolicy](Ps/pC_ibmsbistrappauthenticationsuccessauthenticationpolicy.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_ibm_sterling_b2b_integrator_Ransomware.md)    |