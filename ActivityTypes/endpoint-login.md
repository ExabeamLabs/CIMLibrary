endpoint-login
==============

Description
-----------
A user logged into an endpoint

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | endpoint       |
| Activity      | login          |
| Activity Type | endpoint-login |
| Pretty Name   | Endpoint Login |

Legacy Names
------------
| Success                                                                                                                                                                      | Fail                                                                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| local-logon<br>remote-logon<br>batch-logon<br>kerberos-logon<br>ntlm-logon<br>service-logon<br>remote-access<br>computer-logon<br>nac-logon<br>authentication-successful<br> | local-logon<br>remote-logon<br>batch-logon<br>kerberos-logon<br>ntlm-logon<br>service-logon<br>remote-access<br>computer-logon<br>failed-logon<br>nac-failed-logon<br>authentication-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-loginsuccess) or a [fail](#endpoint-loginfail).


endpoint-login:success
----------------------

| Field             | Core     | Detection | Informational |
| ----------------- | -------- | --------- | ------------- |
| tgs_service_name  |          | &#10003;  |               |
| src_mac           |          | &#10003;  |               |
| login_type        |          | &#10003;  |               |
| domain_user_name  |          |           |               |
| src_host          |          | &#10003;  |               |
| subject_sid       |          |           | &#10003;      |
| logon_type        |          | &#10003;  |               |
| src_ip            |          | &#10003;  |               |
| account_user_name |          |           |               |
| domain            |          | &#10003;  |               |
| dest_ip           |          | &#10003;  |               |
| result_code       |          | &#10003;  |               |
| location          |          | &#10003;  |               |
| user              | &#10003; | &#10003;  |               |
| account           |          | &#10003;  |               |
| cid               |          |           | &#10003;      |

endpoint-login:fail
-------------------

| Field             | Core     | Detection | Informational |
| ----------------- | -------- | --------- | ------------- |
| src_mac           |          | &#10003;  |               |
| failure_code      |          | &#10003;  |               |
| login_type        |          | &#10003;  |               |
| domain_user_name  |          |           |               |
| failure_reason    |          | &#10003;  |               |
| src_host          |          | &#10003;  |               |
| subject_sid       |          |           | &#10003;      |
| logon_type        |          | &#10003;  |               |
| src_ip            |          | &#10003;  |               |
| account_user_name |          |           |               |
| domain            |          | &#10003;  |               |
| dest_ip           |          | &#10003;  |               |
| result_code       |          | &#10003;  |               |
| location          |          | &#10003;  |               |
| user              | &#10003; | &#10003;  |               |
| account           |          | &#10003;  |               |
| cid               |          |           | &#10003;      |