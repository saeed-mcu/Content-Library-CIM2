|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Privileged Activity](../../../UseCases/uc_privileged_activity.md) |  ""endpoint-activity:success""<br> ↳[microsoft-defenderep-endpoint-activity-deviceevents](Ps/pC_microsoftdefenderependpointactivitydeviceevents.md)<br><br> ""endpoint-notification:success""<br> ↳[microsoft-defenderep-endpoint-notification-eventhubbeat](Ps/pC_microsoftdefenderependpointnotificationeventhubbeat.md)<br> ↳[microsoft-defenderep-cef-endpoint-notification-deviceconnected](Ps/pC_microsoftdefenderepcefendpointnotificationdeviceconnected.md)<br><br> ""network-notification:success""<br> ↳[microsoft-defenderep-network-notification-eventhubbeat](Ps/pC_microsoftdefenderepnetworknotificationeventhubbeat.md)<br><br> ""registry-delete:success""<br> ↳[microsoft-windows-registry-eventhubbeat](Ps/pC_microsoftwindowsregistryeventhubbeat.md)<br><br> ""registry-rename:success""<br> ↳[microsoft-windows-registry-eventhubbeat](Ps/pC_microsoftwindowsregistryeventhubbeat.md)<br><br> computer-logon<br> ↳[microsoft-defenderep-endpoint-login-devicelogonevents](Ps/pC_microsoftdefenderependpointlogindevicelogonevents.md)<br><br> dns-response<br> ↳[microsoft-defenderep-dns-response-dnsqueryresponse](Ps/pC_microsoftdefenderepdnsresponsednsqueryresponse.md)<br><br> image-loaded<br> ↳[microsoft-defenderep-dll-load-eventhubbeat](Ps/pC_microsoftdefenderepdllloadeventhubbeat.md)<br><br> registry-write<br> ↳[microsoft-windows-registry-eventhubbeat](Ps/pC_microsoftwindowsregistryeventhubbeat.md)<br> ↳[microsoft-windows-registry-eventhubbeat](Ps/pC_microsoftwindowsregistryeventhubbeat.md)<br><br> task-created<br> ↳[microsoft-defenderep-scheduled_task-create-scheduledtaskcreated](Ps/pC_microsoftdefenderepscheduled_taskcreatescheduledtaskcreated.md)<br> | T1053.005 - Scheduled Task/Job: Scheduled Task<br>T1543.003 - Create or Modify System Process: Windows Service<br> | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_microsoft_microsoft_defender_for_endpoint_Privileged_Activity.md) |