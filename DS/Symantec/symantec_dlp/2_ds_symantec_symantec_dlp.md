|    Use-Case    | Activity Types/Parsers    | MITRE ATT&CK® TTP    | Content    |
|:----:| ---- | ---- | ---- |
|          [Data Access](../../../UseCases/uc_data_access.md)          |  file-read<br> ↳[symantec-dlp-json-file-read-success-fileread](Ps/pC_symantecdlpjsonfilereadsuccessfileread.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br>    | T1083 - File and Directory Discovery<br>    | [<ul><li>24 Rules</li></ul><ul><li>13 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Data_Access.md)        |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  dlp-alert<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp](Ps/pC_symantecdlpcefalerttriggersuccessdlp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-symantecdlp](Ps/pC_symantecdlpcefalerttriggersuccesssymantecdlp.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-blocked](Ps/pC_symantecdlpkvalerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpincident](Ps/pC_symantecdlpkvalerttriggersuccessdlpincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-contentsecurity](Ps/pC_symantecdlpcefalerttriggersuccesscontentsecurity.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpalert](Ps/pC_symantecdlpkvalerttriggersuccessdlpalert.md)<br> ↳[symantec-dlp-str-alert-trigger-success-threatitp](Ps/pC_symantecdlpstralerttriggersuccessthreatitp.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-alert-trigger-success-blocked](Ps/pC_symantecdlpstralerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-riskseverity](Ps/pC_symantecdlpkvalerttriggersuccessriskseverity.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp](Ps/pC_symantecdlpkvalerttriggersuccesssmtp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-applicationname](Ps/pC_symantecdlpcefalerttriggersuccessapplicationname.md)<br> ↳[symantec-dlp-leef-alert-trigger-success-corporatenetwork](Ps/pC_symantecdlpleefalerttriggersuccesscorporatenetwork.md)<br> ↳[symantec-dlp-csv-alert-trigger-success-https](Ps/pC_symantecdlpcsvalerttriggersuccesshttps.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlphost](Ps/pC_symantecdlpkvalerttriggersuccessdlphost.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-incidentid](Ps/pC_symantecdlpkvalerttriggersuccessincidentid.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp-1](Ps/pC_symantecdlpkvalerttriggersuccesssmtp1.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-monitorname](Ps/pC_symantecdlpkvalerttriggersuccessmonitorname.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-endpoint](Ps/pC_symantecdlpkvalerttriggersuccessendpoint.md)<br> ↳[symantec-dlp-json-alert-trigger-success-rule](Ps/pC_symantecdlpjsonalerttriggersuccessrule.md)<br> ↳[symantec-dlp-str-alert-trigger-success-symcdlpsys](Ps/pC_symantecdlpstralerttriggersuccesssymcdlpsys.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-alerttrigger](Ps/pC_symantecdlpkvalerttriggersuccessalerttrigger.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp-1](Ps/pC_symantecdlpcefalerttriggersuccessdlp1.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br>    | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0002 - TA0002<br>TA0010 - TA0010<br>    | [<ul><li>31 Rules</li></ul><ul><li>19 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Data_Exfiltration.md)  |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  dlp-alert<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp](Ps/pC_symantecdlpcefalerttriggersuccessdlp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-symantecdlp](Ps/pC_symantecdlpcefalerttriggersuccesssymantecdlp.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-blocked](Ps/pC_symantecdlpkvalerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpincident](Ps/pC_symantecdlpkvalerttriggersuccessdlpincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-contentsecurity](Ps/pC_symantecdlpcefalerttriggersuccesscontentsecurity.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpalert](Ps/pC_symantecdlpkvalerttriggersuccessdlpalert.md)<br> ↳[symantec-dlp-str-alert-trigger-success-threatitp](Ps/pC_symantecdlpstralerttriggersuccessthreatitp.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-alert-trigger-success-blocked](Ps/pC_symantecdlpstralerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-riskseverity](Ps/pC_symantecdlpkvalerttriggersuccessriskseverity.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp](Ps/pC_symantecdlpkvalerttriggersuccesssmtp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-applicationname](Ps/pC_symantecdlpcefalerttriggersuccessapplicationname.md)<br> ↳[symantec-dlp-leef-alert-trigger-success-corporatenetwork](Ps/pC_symantecdlpleefalerttriggersuccesscorporatenetwork.md)<br> ↳[symantec-dlp-csv-alert-trigger-success-https](Ps/pC_symantecdlpcsvalerttriggersuccesshttps.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlphost](Ps/pC_symantecdlpkvalerttriggersuccessdlphost.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-incidentid](Ps/pC_symantecdlpkvalerttriggersuccessincidentid.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp-1](Ps/pC_symantecdlpkvalerttriggersuccesssmtp1.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-monitorname](Ps/pC_symantecdlpkvalerttriggersuccessmonitorname.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-endpoint](Ps/pC_symantecdlpkvalerttriggersuccessendpoint.md)<br> ↳[symantec-dlp-json-alert-trigger-success-rule](Ps/pC_symantecdlpjsonalerttriggersuccessrule.md)<br> ↳[symantec-dlp-str-alert-trigger-success-symcdlpsys](Ps/pC_symantecdlpstralerttriggersuccesssymcdlpsys.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-alerttrigger](Ps/pC_symantecdlpkvalerttriggersuccessalerttrigger.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp-1](Ps/pC_symantecdlpcefalerttriggersuccessdlp1.md)<br><br> dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br><br> dlp-email-alert-out-failed<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br><br> print-activity<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp-1](Ps/pC_symantecdlpcefalerttriggersuccessdlp1.md)<br> ↳[symantec-dlp-str-printer-activity-success-faxincident](Ps/pC_symantecdlpstrprinteractivitysuccessfaxincident.md)<br><br> usb-insert<br> ↳[symantec-dlp-kv-peripheral-storage-insert-success-devicewas](Ps/pC_symantecdlpkvperipheralstorageinsertsuccessdevicewas.md)<br> ↳[symantec-dlp-kv-peripheral-storage-insert-success-allowedthedevice](Ps/pC_symantecdlpkvperipheralstorageinsertsuccessallowedthedevice.md)<br> | T1020 - Automated Exfiltration<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1071 - Application Layer Protocol<br>T1091 - Replication Through Removable Media<br>T1114.001 - T1114.001<br>TA0010 - TA0010<br> | [<ul><li>81 Rules</li></ul><ul><li>40 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Data_Leak.md)          |
|    [Malware](../../../UseCases/uc_malware.md)    |  dlp-alert<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp](Ps/pC_symantecdlpcefalerttriggersuccessdlp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-symantecdlp](Ps/pC_symantecdlpcefalerttriggersuccesssymantecdlp.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-blocked](Ps/pC_symantecdlpkvalerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpincident](Ps/pC_symantecdlpkvalerttriggersuccessdlpincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-contentsecurity](Ps/pC_symantecdlpcefalerttriggersuccesscontentsecurity.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlpalert](Ps/pC_symantecdlpkvalerttriggersuccessdlpalert.md)<br> ↳[symantec-dlp-str-alert-trigger-success-threatitp](Ps/pC_symantecdlpstralerttriggersuccessthreatitp.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-alert-trigger-success-blocked](Ps/pC_symantecdlpstralerttriggersuccessblocked.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-riskseverity](Ps/pC_symantecdlpkvalerttriggersuccessriskseverity.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp](Ps/pC_symantecdlpkvalerttriggersuccesssmtp.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-applicationname](Ps/pC_symantecdlpcefalerttriggersuccessapplicationname.md)<br> ↳[symantec-dlp-leef-alert-trigger-success-corporatenetwork](Ps/pC_symantecdlpleefalerttriggersuccesscorporatenetwork.md)<br> ↳[symantec-dlp-csv-alert-trigger-success-https](Ps/pC_symantecdlpcsvalerttriggersuccesshttps.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-dlphost](Ps/pC_symantecdlpkvalerttriggersuccessdlphost.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-incidentid](Ps/pC_symantecdlpkvalerttriggersuccessincidentid.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-smtp-1](Ps/pC_symantecdlpkvalerttriggersuccesssmtp1.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-monitorname](Ps/pC_symantecdlpkvalerttriggersuccessmonitorname.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-endpoint](Ps/pC_symantecdlpkvalerttriggersuccessendpoint.md)<br> ↳[symantec-dlp-json-alert-trigger-success-rule](Ps/pC_symantecdlpjsonalerttriggersuccessrule.md)<br> ↳[symantec-dlp-str-alert-trigger-success-symcdlpsys](Ps/pC_symantecdlpstralerttriggersuccesssymcdlpsys.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-alerttrigger](Ps/pC_symantecdlpkvalerttriggersuccessalerttrigger.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-cef-alert-trigger-success-dlp-1](Ps/pC_symantecdlpcefalerttriggersuccessdlp1.md)<br><br> dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br>    | T1003.002 - T1003.002<br>T1190 - Exploit Public Fasing Application<br>T1505.003 - Server Software Component: Web Shell<br>T1547.001 - T1547.001<br>TA0002 - TA0002<br>    | [<ul><li>14 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Phishing.md)    |
|      [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)      |  dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br><br> dlp-email-alert-out-failed<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br><br> file-read<br> ↳[symantec-dlp-json-file-read-success-fileread](Ps/pC_symantecdlpjsonfilereadsuccessfileread.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_symantec_symantec_dlp_Privilege_Abuse.md)    |
|  [Privileged Activity](../../../UseCases/uc_privileged_activity.md)  |  dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br><br> dlp-email-alert-out-failed<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br><br> file-read<br> ↳[symantec-dlp-json-file-read-success-fileread](Ps/pC_symantecdlpjsonfilereadsuccessfileread.md)<br><br> file-write<br> ↳[symantec-dlp-json-file-write-success-filewrite](Ps/pC_symantecdlpjsonfilewritesuccessfilewrite.md)<br> ↳[symantec-dlp-csv-file-write-success-usbtransfer](Ps/pC_symantecdlpcsvfilewritesuccessusbtransfer.md)<br> ↳[symantec-dlp-cef-file-write-success-usbdrives](Ps/pC_symantecdlpceffilewritesuccessusbdrives.md)<br> ↳[symantec-dlp-kv-alert-trigger-success-policyviolated](Ps/pC_symantecdlpkvalerttriggersuccesspolicyviolated.md)<br>    | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_symantec_symantec_dlp_Privileged_Activity.md)    |
| [Workforce Protection](../../../UseCases/uc_workforce_protection.md) |  dlp-email-alert-out<br> ↳[symantec-dlp-kv-email-send-incident-1](Ps/pC_symantecdlpkvemailsendincident1.md)<br> ↳[symantec-dlp-kv-email-send-incident](Ps/pC_symantecdlpkvemailsendincident.md)<br> ↳[symantec-dlp-str-email-send-protectmanager](Ps/pC_symantecdlpstremailsendprotectmanager.md)<br> ↳[symantec-dlp-str-email-receive-incident](Ps/pC_symantecdlpstremailreceiveincident.md)<br> ↳[symantec-dlp-leef-alert-email-modified](Ps/pC_symantecdlpleefalertemailmodified.md)<br> ↳[symantec-dlp-kv-email-send-confidentialdata](Ps/pC_symantecdlpkvemailsendconfidentialdata.md)<br> ↳[symantec-dlp-leef-email-send-success-corporatenetwork](Ps/pC_symantecdlpleefemailsendsuccesscorporatenetwork.md)<br> ↳[symantec-dlp-kv-email-send-vontu](Ps/pC_symantecdlpkvemailsendvontu.md)<br> ↳[symantec-dlp-kv-email-send-sender](Ps/pC_symantecdlpkvemailsendsender.md)<br> ↳[symantec-dlp-str-email-send-success-smtp](Ps/pC_symantecdlpstremailsendsuccesssmtp.md)<br>    | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_symantec_symantec_dlp_Workforce_Protection.md) |