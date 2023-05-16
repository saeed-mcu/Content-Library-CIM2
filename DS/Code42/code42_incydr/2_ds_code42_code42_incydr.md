|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> file-delete<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-read<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br>    | T1003.001 - T1003.001<br>T1003.002 - T1003.002<br>T1003.003 - T1003.003<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br>    | [<ul><li>72 Rules</li></ul><ul><li>38 Models</li></ul>](RM/r_m_code42_code42_incydr_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> file-delete<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-read<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br>    | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>43 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_code42_code42_incydr_Data_Access.md)    |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  dlp-alert<br> ↳[code42-incydr-sk4-alert-trigger-success-cloudstorage](Ps/pC_code42incydrsk4alerttriggersuccesscloudstorage.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-publicshares](Ps/pC_code42incydrsk4alerttriggersuccesspublicshares.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-sourcecode](Ps/pC_code42incydrsk4alerttriggersuccesssourcecode.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br>    | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0002 - TA0002<br>TA0010 - TA0010<br>    | [<ul><li>31 Rules</li></ul><ul><li>19 Models</li></ul>](RM/r_m_code42_code42_incydr_Data_Exfiltration.md)       |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> dlp-alert<br> ↳[code42-incydr-sk4-alert-trigger-success-cloudstorage](Ps/pC_code42incydrsk4alerttriggersuccesscloudstorage.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-publicshares](Ps/pC_code42incydrsk4alerttriggersuccesspublicshares.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-sourcecode](Ps/pC_code42incydrsk4alerttriggersuccesssourcecode.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> usb-insert<br> ↳[code42-incydr-json-peripheral-storage-insert-success-deviceappeared](Ps/pC_code42incydrjsonperipheralstorageinsertsuccessdeviceappeared.md)<br>    | T1020 - Automated Exfiltration<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1071 - Application Layer Protocol<br>T1091 - Replication Through Removable Media<br>T1114.001 - T1114.001<br>T1114.003 - Email Collection: Email Forwarding Rule<br>TA0010 - TA0010<br> | [<ul><li>46 Rules</li></ul><ul><li>22 Models</li></ul>](RM/r_m_code42_code42_incydr_Data_Leak.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> dlp-alert<br> ↳[code42-incydr-sk4-alert-trigger-success-cloudstorage](Ps/pC_code42incydrsk4alerttriggersuccesscloudstorage.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-publicshares](Ps/pC_code42incydrsk4alerttriggersuccesspublicshares.md)<br> ↳[code42-incydr-sk4-alert-trigger-success-sourcecode](Ps/pC_code42incydrsk4alerttriggersuccesssourcecode.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br>    | T1003.002 - T1003.002<br>T1078 - Valid Accounts<br>T1505.003 - Server Software Component: Web Shell<br>T1547.001 - T1547.001<br>TA0002 - TA0002<br>    | [<ul><li>14 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_code42_code42_incydr_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> file-delete<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-download<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-read<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-upload<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_code42_code42_incydr_Privilege_Abuse.md)    |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳[code42-incydr-sk4-app-activity-success-appclient](Ps/pC_code42incydrsk4appactivitysuccessappclient.md)<br><br> file-delete<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-download<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-read<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-upload<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br><br> file-write<br> ↳[code42-incydr-str-file-success-logcollector](Ps/pC_code42incydrstrfilesuccesslogcollector.md)<br> ↳[code42-incydr-json-file-delete-success-deviceaddress](Ps/pC_code42incydrjsonfiledeletesuccessdeviceaddress.md)<br> ↳[code42-incydr-csv-file-delete-success-code42logcollector](Ps/pC_code42incydrcsvfiledeletesuccesscode42logcollector.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_code42_code42_incydr_Privileged_Activity.md)       |