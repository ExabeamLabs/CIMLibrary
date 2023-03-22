scheduled_task-disable
======================

Description
-----------
A scheduled task was disabled, blocking it from triggering

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | scheduled_task         |
| Activity      | disable                |
| Activity Type | scheduled_task-disable |
| Pretty Name   | Scheduled_task Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-disablesuccess) or a [fail](#scheduled_task-disablefail).


scheduled_task-disable:success
------------------------------

There are no fields for this activity type.


scheduled_task-disable:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |