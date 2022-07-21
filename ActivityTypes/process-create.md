process-create
==============

Description
-----------
A process was executed

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-createsuccess) or a [fail](#process-createfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | process        |
| Activity      | create         |
| Activity Type | process-create |
| Pretty Name   | Process Create |
| Legacy Name   |                |

process-create:success
----------------------

| Field                       | Core | Detection | Informational |
| --------------------------- | ---- | --------- | ------------- |
| parent_process_id           |      | &#10003;  |               |
| parent_process_command_line |      | &#10003;  |               |
| parent_process_name         |      | &#10003;  |               |
| parent_process_dir          |      | &#10003;  |               |
| parent_process_path         |      | &#10003;  |               |

process-create:fail
-------------------

| Field                       | Core | Detection | Informational |
| --------------------------- | ---- | --------- | ------------- |
| parent_process_id           |      | &#10003;  |               |
| failure_code                |      | &#10003;  |               |
| parent_process_command_line |      | &#10003;  |               |
| parent_process_name         |      | &#10003;  |               |
| failure_reason              |      | &#10003;  |               |
| parent_process_dir          |      | &#10003;  |               |
| parent_process_path         |      | &#10003;  |               |