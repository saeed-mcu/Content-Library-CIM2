Rules by Product and UseCase
============================
Vendor: Microsoft
-----------------
### Product: [Event Viewer - TaskScheduler](../ds_microsoft_event_viewer_-_taskscheduler.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|   2   |   2    |         4          |       1        |    1    |

| Event Type   | Rules    | Models    |
| ---- | ---- | ---- |
| task-created | <b>T1053 - Scheduled Task/Job</b><br> ↳ <b>WTC-HT-EXEC</b>: Non-Executive user created a scheduled task/service on executive asset<br> ↳ <b>WTC-HT-PRIV</b>: Non-Privileged user created a scheduled task/service on privileged asset<br><br><b>T1053.005 - Scheduled Task/Job: Scheduled Task</b><br> ↳ <b>WTC-HT-EXEC</b>: Non-Executive user created a scheduled task/service on executive asset<br> ↳ <b>WTC-HT-PRIV</b>: Non-Privileged user created a scheduled task/service on privileged asset<br><br><b>T1543 - Create or Modify System Process</b><br> ↳ <b>WTC-HT-EXEC</b>: Non-Executive user created a scheduled task/service on executive asset<br> ↳ <b>WTC-HT-PRIV</b>: Non-Privileged user created a scheduled task/service on privileged asset<br><br><b>T1543.003 - Create or Modify System Process: Windows Service</b><br> ↳ <b>WTC-HT-EXEC</b>: Non-Executive user created a scheduled task/service on executive asset<br> ↳ <b>WTC-HT-PRIV</b>: Non-Privileged user created a scheduled task/service on privileged asset |  • <b>AL-HT-PRIV</b>: Privilege Users Assets<br> • <b>AL-HT-EXEC</b>: Executive Assets |