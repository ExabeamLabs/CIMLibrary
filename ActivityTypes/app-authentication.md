app-authentication
==================

Description
-----------
A part of an identification process to an app that is not the login

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-authenticationsuccess) or a [fail](#app-authenticationfail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | app                |
| Activity      | authentication     |
| Activity Type | app-authentication |
| Pretty Name   | App Authentication |
| Legacy Name   |                    |

app-authentication:success
--------------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| user                | &#10003; |           |               |
| authentication_type |          |           |               |

app-authentication:fail
-----------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| user                | &#10003; |           |               |
| authentication_type |          |           |               |