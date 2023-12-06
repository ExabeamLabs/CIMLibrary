app-authentication
==================

Description
-----------
A part of an identification process to an app that is not the login

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | app                |
| Activity      | authentication     |
| Activity Type | app-authentication |
| Pretty Name   | App Authentication |

Legacy Names
------------
| Success                                    | Fail                                   |
| ------------------------------------------ | -------------------------------------- |
| app-login<br>authentication-successful<br> | app-login<br>authentication-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-authenticationsuccess) or a [fail](#app-authenticationfail).


app-authentication:success
--------------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| auth_type       |          |           |               |
| os              |          | &#10003;  |               |
| mfa_country     |          | &#10003;  |               |
| mime            |          | &#10003;  |               |
| local_user_name |          |           |               |
| src_host        |          | &#10003;  |               |
| src_ip          |          | &#10003;  |               |
| browser         |          | &#10003;  |               |
| fingerprint     |          | &#10003;  |               |
| mfa_device      |          | &#10003;  |               |
| user            | &#10003; | &#10003;  |               |
| operation       |          | &#10003;  |               |
| user_agent      |          | &#10003;  |               |
| object          |          | &#10003;  |               |

app-authentication:fail
-----------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| auth_type       |          |           |               |
| failure_code    |          | &#10003;  |               |
| os              |          | &#10003;  |               |
| mfa_country     |          | &#10003;  |               |
| mime            |          | &#10003;  |               |
| local_user_name |          |           |               |
| failure_reason  |          | &#10003;  |               |
| src_host        |          | &#10003;  |               |
| src_ip          |          | &#10003;  |               |
| browser         |          | &#10003;  |               |
| fingerprint     |          | &#10003;  |               |
| mfa_device      |          | &#10003;  |               |
| user            | &#10003; | &#10003;  |               |
| operation       |          | &#10003;  |               |
| user_agent      |          | &#10003;  |               |
| object          |          | &#10003;  |               |