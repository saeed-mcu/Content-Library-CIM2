|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
|         [Cryptomining](../../../UseCases/uc_cryptomining.md)         |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>T1496 - Resource Hijacking<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Cryptomining.md)    |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1041 - Exfiltration Over C2 Channel<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1567 - Exfiltration Over Web Service<br>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage<br>T1568 - Dynamic Resolution<br>T1568.002 - Dynamic Resolution: Domain Generation Algorithms<br>    | [<ul><li>8 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_cms_Data_Exfiltration.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1041 - Exfiltration Over C2 Channel<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1567 - Exfiltration Over Web Service<br>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage<br>    | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_cms_Data_Leak.md)    |
|     [Lateral Movement](../../../UseCases/uc_lateral_movement.md)     |  security-alert<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-xml-alert-trigger-success-fenotify](Ps/pC_fireeyenetworksecurityxmlalerttriggersuccessfenotify.md)<br><br> web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1190 - Exploit Public Fasing Application<br>TA0011 - TA0011<br>    | [<ul><li>12 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  security-alert<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-xml-alert-trigger-success-fenotify](Ps/pC_fireeyenetworksecurityxmlalerttriggersuccessfenotify.md)<br><br> web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br> | T1071 - Application Layer Protocol<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1189 - Drive-by Compromise<br>T1190 - Exploit Public Fasing Application<br>T1204.001 - T1204.001<br>T1566.002 - Phishing: Spearphishing Link<br>T1568.002 - Dynamic Resolution: Domain Generation Algorithms<br>TA0002 - TA0002<br>TA0011 - TA0011<br> | [<ul><li>32 Rules</li></ul><ul><li>9 Models</li></ul>](RM/r_m_fireeye_fireeye_cms_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1189 - Drive-by Compromise<br>T1204.001 - T1204.001<br>T1534 - Internal Spearphishing<br>T1566.002 - Phishing: Spearphishing Link<br>T1598.003 - T1598.003<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Phishing.md)    |
|      [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)      |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Privilege_Abuse.md)    |
|  [Privileged Activity](../../../UseCases/uc_privileged_activity.md)  |  security-alert<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-emailsecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyeemailsecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-xml-alert-trigger-success-fenotify](Ps/pC_fireeyenetworksecurityxmlalerttriggersuccessfenotify.md)<br><br> web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1071.001 - Application Layer Protocol: Web Protocols<br>T1078 - Valid Accounts<br>T1102 - Web Service<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br><br> web-activity-denied<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>TA0011 - TA0011<br>    | [<ul><li>5 Rules</li></ul>](RM/r_m_fireeye_fireeye_cms_Ransomware.md)    |
| [Workforce Protection](../../../UseCases/uc_workforce_protection.md) |  web-activity-allowed<br> ↳[fireeye-networksecurity-json-alert-trigger-success-srcipv4](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccesssrcipv4.md)<br> ↳[fireeye-escm-json-alert-trigger-success-fireeyecm](Ps/pC_fireeyeescmjsonalerttriggersuccessfireeyecm.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-deviceseverity](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessdeviceseverity.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-malwareobject](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessmalwareobject.md)<br> ↳[fireeye-networksecurity-cef-alert-trigger-success-fireeye](Ps/pC_fireeyenetworksecuritycefalerttriggersuccessfireeye.md)<br> ↳[fireeye-networksecurity-json-alert-trigger-success-product](Ps/pC_fireeyenetworksecurityjsonalerttriggersuccessproduct.md)<br> ↳[fireeye-networksecurity-leef-alert-trigger-success-fireeyemps](Ps/pC_fireeyenetworksecurityleefalerttriggersuccessfireeyemps.md)<br> ↳[fireeye-networksecurity-json-http-session-dstdomain](Ps/pC_fireeyenetworksecurityjsonhttpsessiondstdomain.md)<br>    | T1071.001 - Application Layer Protocol: Web Protocols<br>    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fireeye_fireeye_cms_Workforce_Protection.md) |