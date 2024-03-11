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

| Field       | Core     | Detection | Informational |
| ----------- | -------- | --------- | ------------- |
| auth_type   |          |           |               |
| mfa_country |          | &#10003;  |               |
| mfa_device  |          | &#10003;  |               |
| user        | &#10003; |           |               |

app-authentication:fail
-----------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| auth_type      |          |           |               |
| failure_code   |          | &#10003;  |               |
| mfa_country    |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| mfa_device     |          | &#10003;  |               |
| user           | &#10003; |           |               |