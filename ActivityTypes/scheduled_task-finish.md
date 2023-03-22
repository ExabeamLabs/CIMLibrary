scheduled_task-finish
=====================

Description
-----------
An occurance of a scheduled task was done executing

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | scheduled_task        |
| Activity      | finish                |
| Activity Type | scheduled_task-finish |
| Pretty Name   | Scheduled_task Finish |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-finishsuccess) or a [fail](#scheduled_task-finishfail).


scheduled_task-finish:success
-----------------------------

There are no fields for this activity type.


scheduled_task-finish:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |