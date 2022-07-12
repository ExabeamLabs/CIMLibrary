endpoint-authentication
=======================

Description
-----------
A part of an identification process to an endpoint that is not the login

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-authenticationsuccess) or a [fail](#endpoint-authenticationfail).

| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | endpoint                |
| Activity      | authentication          |
| Activity Type | endpoint-authentication |
| Pretty Name   | Endpoint Authentication |
| Legacy Name   |                         |

endpoint-authentication:success
-------------------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| domain              |          |           |               |
| user                | &#10003; | &#10003;  |               |
| authentication_type |          | &#10003;  |               |

endpoint-authentication:fail
----------------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| domain              |          |           |               |
| user                | &#10003; | &#10003;  |               |
| authentication_type |          | &#10003;  |               |