process-token-assign
====================

Description
-----------
A process token was assigned to a process

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-token-assignsuccess) or a [fail](#process-token-assignfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | process              |
| Activity      | token-assign         |
| Activity Type | process-token-assign |
| Pretty Name   | Process Token Assign |
| Legacy Name   |                      |

process-token-assign:success
----------------------------

There are no fields for this activity type.


process-token-assign:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |