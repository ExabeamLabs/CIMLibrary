scheduled_task-modify
=====================

Description
-----------
The configuration of a scheduled task was changed

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | scheduled_task        |
| Activity      | modify                |
| Activity Type | scheduled_task-modify |
| Pretty Name   | Scheduled_task Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-modifysuccess) or a [fail](#scheduled_task-modifyfail).


scheduled_task-modify:success
-----------------------------

| Field | Core | Detection | Informational |
| ----- | ---- | --------- | ------------- |
| cid   |      |           | &#10003;      |

scheduled_task-modify:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| cid            |      |           | &#10003;      |