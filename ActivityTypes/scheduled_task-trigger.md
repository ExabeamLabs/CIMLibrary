scheduled_task-trigger
======================

Description
-----------
An occurance of a scheduled task was executed

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-triggersuccess) or a [fail](#scheduled_task-triggerfail).

| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | scheduled_task         |
| Activity      | trigger                |
| Activity Type | scheduled_task-trigger |
| Pretty Name   | Scheduled_task Trigger |
| Legacy Name   |                        |

scheduled_task-trigger:success
------------------------------

There are no fields for this activity type.


scheduled_task-trigger:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |