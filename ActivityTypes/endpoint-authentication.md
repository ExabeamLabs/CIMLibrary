endpoint-authentication
=======================

Description
-----------
A part of an identification process to an endpoint that is not the login

Parameters
----------
| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | endpoint                |
| Activity      | authentication          |
| Activity Type | endpoint-authentication |
| Pretty Name   | Endpoint Authentication |

Legacy Names
------------
| Success                                                      | Fail                                                            |
| ------------------------------------------------------------ | --------------------------------------------------------------- |
| authentication-successful<br>kerberos-logon<br>nac-logon<br> | authentication-failed<br>kerberos-logon<br>nac-failed-logon<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-authenticationsuccess) or a [fail](#endpoint-authenticationfail).


endpoint-authentication:success
-------------------------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| tgs_service_name |          | &#10003;  |               |
| auth_type        |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

endpoint-authentication:fail
----------------------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| auth_type        |          | &#10003;  |               |
| failure_code     |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| failure_reason   |          | &#10003;  |               |
| logon_type       |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |