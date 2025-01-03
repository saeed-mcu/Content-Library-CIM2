Rules by Product and UseCase
============================
Vendor: Amazon
--------------
### Product: [AWS CloudTrail](../ds_amazon_aws_cloudtrail.md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE ATT&CK® TTPs | Activity Types | Parsers |
|:-----:|:------:|:------------------:|:--------------:|:-------:|
|  11   |   7    |         7          |       10       |    6    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity    | <b>T1098 - Account Manipulation</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>EM-InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions<br><br><b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>EM-InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity |  • <b>EM-InB-Perm-N</b>: Models users who give mailbox permissions<br> • <b>APP-AT-PRIV</b>: Privileged application activities |
| app-activity-failed       | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| app-login    | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application    |    |
| aws-identity-addtogroup   | <b>TA0004 - TA0004</b><br> ↳ <b>AWS-UserAddToGroup-Org-F</b>: First time the add user to group operation was performed by user in AWS    |  • <b>AWS-UserAddToGroup-Org</b>: AWS users who performed add user to group operations    |
| aws-identity-creds-write  | <b>TA0004 - TA0004</b><br> ↳ <b>AWS-UserCreateAccessKey-Org-F</b>: First time access key creation operation for user in AWS    |  • <b>AWS-UserCreateAccessKey-Org</b>: AWS access key creations    |
| aws-identity-list         | <b>T1087 - Account Discovery</b><br> ↳ <b>AWS-UserIdentityEnum-Org-F</b>: First time identity enumeration for user in AWS<br><br><b>T1087.004 - T1087.004</b><br> ↳ <b>AWS-UserIdentityEnum-Org-F</b>: First time identity enumeration for user in AWS    |  • <b>AWS-UserIdentityEnum-Org</b>: AWS users and groups enumerations    |
| aws-identity-loginprofile | <b>TA0003 - TA0003</b><br> ↳ <b>AWS-UserWriteLoginProfile-Org-F</b>: First time this user updated or created a login profile in AWS    |  • <b>AWS-UserWriteLoginProfile-Org</b>: AWS users who created or updated login profiles    |
| aws-identity-write        | <b>TA0004 - TA0004</b><br> ↳ <b>AWS-UserCreateUser-Org-F</b>: First time user creation operation for user in AWS    |  • <b>AWS-UserCreateUser-Org</b>: AWS Users who created users in the AWS    |
| aws-identity-write-failed | <b>TA0004 - TA0004</b><br> ↳ <b>AWS-UserCreateUser-Org-F</b>: First time user creation operation for user in AWS    |  • <b>AWS-UserCreateUser-Org</b>: AWS Users who created users in the AWS    |
| failed-app-login          | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |