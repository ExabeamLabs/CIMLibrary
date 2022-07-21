app-login
=========

Description
-----------
A user logged in to an application

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-loginsuccess) or a [fail](#app-loginfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | app       |
| Activity      | login     |
| Activity Type | app-login |
| Pretty Name   | App Login |
| Legacy Name   |           |

app-login:success
-----------------

| Field | Core     | Detection | Informational |
| ----- | -------- | --------- | ------------- |
| user  | &#10003; |           |               |

app-login:fail
--------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; |           |               |