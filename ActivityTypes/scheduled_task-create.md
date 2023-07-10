scheduled_task-create
=====================

Description
-----------
A scheduled task was created

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | scheduled_task        |
| Activity      | create                |
| Activity Type | scheduled_task-create |
| Pretty Name   | Scheduled_task Create |

Legacy Names
------------
| Success          | Fail             |
| ---------------- | ---------------- |
| task-created<br> | task-created<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#scheduled_task-createsuccess) or a [fail](#scheduled_task-createfail).


scheduled_task-create:success
-----------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| process_name    |      | &#10003;  |               |
| local_user_name |      |           |               |
| process_path    |      | &#10003;  |               |
| user            |      | &#10003;  |               |

scheduled_task-create:fail
--------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| process_name    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |
| process_path    |      | &#10003;  |               |
| user            |      | &#10003;  |               |