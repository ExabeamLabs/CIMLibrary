scheduled_task-start
====================

Description
-----------
A scheduled task was configured to start, marking the moment where it would start searching for its triggers.

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | scheduled_task       |
| Activity      | start                |
| Activity Type | scheduled_task-start |
| Pretty Name   | Scheduled_task Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-startsuccess) or a [fail](#scheduled_task-startfail).


scheduled_task-start:success
----------------------------

There are no fields for this activity type.


scheduled_task-start:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |