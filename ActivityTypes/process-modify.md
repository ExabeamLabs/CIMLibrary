process-modify
==============

Description
-----------
The properties of a process were changed as it was running

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-modifysuccess) or a [fail](#process-modifyfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | process        |
| Activity      | modify         |
| Activity Type | process-modify |
| Pretty Name   | Process Modify |
| Legacy Name   |                |

process-modify:success
----------------------

There are no fields for this activity type.


process-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |