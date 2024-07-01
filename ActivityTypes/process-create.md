process-create
==============

Description
-----------
A process was executed

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | process        |
| Activity      | create         |
| Activity Type | process-create |
| Pretty Name   | Process Create |

Legacy Names
------------
| Success             | Fail                       |
| ------------------- | -------------------------- |
| process-created<br> | process-created-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-createsuccess) or a [fail](#process-createfail).


process-create:success
----------------------

| Field                       | Core | Detection | Informational |
| --------------------------- | ---- | --------- | ------------- |
| parent_process_id           |      | &#10003;  |               |
| parent_process_command_line |      | &#10003;  |               |
| command_module              |      | &#10003;  |               |
| parent_process_name         |      | &#10003;  |               |
| domain_user_name            |      |           |               |
| parent_process_dir          |      | &#10003;  |               |
| hash_sha256                 |      | &#10003;  |               |
| dest_user_entity_id         |      |           |               |
| process_guid                |      | &#10003;  |               |
| domain                      |      | &#10003;  |               |
| process_integrity           |      | &#10003;  |               |
| dest_host                   |      | &#10003;  |               |
| parent_process_guid         |      | &#10003;  |               |
| control_panel_item          |      | &#10003;  |               |
| parent_process_path         |      | &#10003;  |               |
| user                        |      | &#10003;  |               |
| dest_device_entity_id       |      |           |               |
| cid                         |      |           | &#10003;      |

process-create:fail
-------------------

| Field                       | Core | Detection | Informational |
| --------------------------- | ---- | --------- | ------------- |
| parent_process_id           |      | &#10003;  |               |
| failure_code                |      | &#10003;  |               |
| parent_process_command_line |      | &#10003;  |               |
| parent_process_name         |      | &#10003;  |               |
| domain_user_name            |      |           |               |
| failure_reason              |      | &#10003;  |               |
| parent_process_dir          |      | &#10003;  |               |
| hash_sha256                 |      | &#10003;  |               |
| process_guid                |      | &#10003;  |               |
| domain                      |      | &#10003;  |               |
| process_integrity           |      | &#10003;  |               |
| dest_host                   |      | &#10003;  |               |
| parent_process_guid         |      | &#10003;  |               |
| control_panel_item          |      | &#10003;  |               |
| parent_process_path         |      | &#10003;  |               |
| user                        |      | &#10003;  |               |
| cid                         |      |           | &#10003;      |