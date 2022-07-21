scheduled_task-delete
=====================

Description
-----------
A scheduled task was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-deletesuccess) or a [fail](#scheduled_task-deletefail).

| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | scheduled_task        |
| Activity      | delete                |
| Activity Type | scheduled_task-delete |
| Pretty Name   | Scheduled_task Delete |
| Legacy Name   |                       |

scheduled_task-delete:success
-----------------------------

There are no fields for this activity type.


scheduled_task-delete:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |