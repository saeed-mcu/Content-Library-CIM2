|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>39 Rules</li></ul><ul><li>24 Models</li></ul>](RM/r_m_wazuh_wazuh_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>19 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_wazuh_wazuh_Data_Access.md)    |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1020 - Automated Exfiltration<br>T1071 - Application Layer Protocol<br>TA0010 - TA0010<br>    | [<ul><li>29 Rules</li></ul><ul><li>18 Models</li></ul>](RM/r_m_wazuh_wazuh_Data_Exfiltration.md)       |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1020 - Automated Exfiltration<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1071 - Application Layer Protocol<br>T1091 - Replication Through Removable Media<br>T1114.003 - Email Collection: Email Forwarding Rule<br>TA0010 - TA0010<br> | [<ul><li>46 Rules</li></ul><ul><li>22 Models</li></ul>](RM/r_m_wazuh_wazuh_Data_Leak.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_wazuh_wazuh_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>TA0002 - TA0002<br>    | [<ul><li>5 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_wazuh_wazuh_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_wazuh_wazuh_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_wazuh_wazuh_Privilege_Escalation.md)      |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_wazuh_wazuh_Privileged_Activity.md)       |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  ""app-notification:success""<br> ↳[wazuh-w-cef-app-notification-success-wazuhalerts](Ps/pC_wazuhwcefappnotificationsuccesswazuhalerts.md)<br><br> ""endpoint-activity:success""<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts-1](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts1.md)<br> ↳[wazuh-w-json-endpoint-activity-success-wazuhalerts](Ps/pC_wazuhwjsonendpointactivitysuccesswazuhalerts.md)<br><br> ""peripheral_storage-remove:success""<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br> ↳[wazuh-w-json-peripheral_storage-remove-success-usbdevicedisconnected](Ps/pC_wazuhwjsonperipheral_storageremovesuccessusbdevicedisconnected.md)<br><br> app-activity<br> ↳[wazuh-w-cef-app-activity-success-wazuhalerts](Ps/pC_wazuhwcefappactivitysuccesswazuhalerts.md)<br><br> dlp-alert<br> ↳[wazuh-w-json-alert-trigger-wazuhalerts](Ps/pC_wazuhwjsonalerttriggerwazuhalerts.md)<br><br> usb-insert<br> ↳[wazuh-w-json-peripheral_storage-insert-success-wazuhalerts](Ps/pC_wazuhwjsonperipheral_storageinsertsuccesswazuhalerts.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_wazuh_wazuh_Ransomware.md)    |