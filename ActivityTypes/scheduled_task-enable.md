scheduled_task-enable
=====================

Description
-----------
A scheduled task was enabled, allowing it to trigger

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | scheduled_task        |
| Activity      | enable                |
| Activity Type | scheduled_task-enable |
| Pretty Name   | Scheduled_task Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-enablesuccess) or a [fail](#scheduled_task-enablefail).


scheduled_task-enable:success
-----------------------------

There are no fields for this activity type.


scheduled_task-enable:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |