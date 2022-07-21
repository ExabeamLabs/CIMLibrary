call-send
=========

Description
-----------
A user has called another user

The possible fields for this activity type will vary depending on whether the activity was a [success](#call-sendsuccess) or a [fail](#call-sendfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | call      |
| Activity      | send      |
| Activity Type | call-send |
| Pretty Name   | Call Send |
| Legacy Name   |           |

call-send:success
-----------------

There are no fields for this activity type.


call-send:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |