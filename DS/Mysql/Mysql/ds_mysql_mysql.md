Vendor: Mysql
=============
Product: Mysql
--------------
| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|  18   |   10   |     1      |       1        |    1    |

|    Use-Case    | Activity Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  database-query<br> ↳[mysql-m-sk4-database-query-success-loggeraccount](Ps/pC_mysqlmsk4databasequerysuccessloggeraccount.md)<br> ↳[mysql-m-csv-database-query-success-query](Ps/pC_mysqlmcsvdatabasequerysuccessquery.md)<br> ↳[mysql-m-sk4-database-query-success-message](Ps/pC_mysqlmsk4databasequerysuccessmessage.md)<br> | T1213 - Data from Information Repositories<br> | [<ul><li>18 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_mysql_mysql_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  database-query<br> ↳[mysql-m-sk4-database-query-success-loggeraccount](Ps/pC_mysqlmsk4databasequerysuccessloggeraccount.md)<br> ↳[mysql-m-csv-database-query-success-query](Ps/pC_mysqlmcsvdatabasequerysuccessquery.md)<br> ↳[mysql-m-sk4-database-query-success-message](Ps/pC_mysqlmsk4databasequerysuccessmessage.md)<br> | T1213 - Data from Information Repositories<br> | [<ul><li>18 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_mysql_mysql_Data_Access.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection                                                                              | Command and Control | Exfiltration | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------- | ------------------- | ------------ | ------ |
|                |           |             |                      |                 |                   |           |                  | [Data from Information Repositories](https://attack.mitre.org/techniques/T1213)<br><br> |                     |              |        |