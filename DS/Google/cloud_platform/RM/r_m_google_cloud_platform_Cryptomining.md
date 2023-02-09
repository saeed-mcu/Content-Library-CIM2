Rules by Product and UseCase
============================
Vendor: Google
--------------
### Product: [Cloud Platform](../ds_google_cloud_platform.md)
### Use-Case: [Cryptomining](../../../../UseCases/uc_cryptomining.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|   1   |   1    |         2          |       1        |    1    |

| Event Type          | Rules    | Models    |
| ---- | ---- | ---- |
| gcp-instance-create | <b>T1074 - Data Staged</b><br> ↳ <b>GCP-UserCreateInstance-Org-F</b>: First time instance creation for user<br><br><b>T1496 - Resource Hijacking</b><br> ↳ <b>GCP-UserCreateInstance-Org-F</b>: First time instance creation for user |  • <b>GCP-UserCreateInstance-Org</b>: Users who created an instance in GCP |