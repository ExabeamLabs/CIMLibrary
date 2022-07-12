endpoint-login
==============

Description
-----------
A user logged into an endpoint

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-loginsuccess) or a [fail](#endpoint-loginfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | endpoint       |
| Activity      | login          |
| Activity Type | endpoint-login |
| Pretty Name   | Endpoint Login |
| Legacy Name   |                |

endpoint-login:success
----------------------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| login_type |          | &#10003;  |               |
| domain     |          | &#10003;  |               |
| user       | &#10003; | &#10003;  |               |

endpoint-login:fail
-------------------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| login_type |          | &#10003;  |               |
| domain     |          | &#10003;  |               |
| user       | &#10003; | &#10003;  |               |