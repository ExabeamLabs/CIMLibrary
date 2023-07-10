symantec advanced threat protection
===================================

Expression
----------

product = "symantec edr"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| src_ip           |      | &#10003;  |               |
| event_code       |      |           | &#10003;      |
| domain           |      | &#10003;  |               |
| dest_ip          |      | &#10003;  |               |
| domain_user_name |      |           |               |
| user             |      | &#10003;  |               |

Activity Types
--------------

| Activity Type  | Field                | Status  | Core     | Detection | Informational |
| -------------- | -------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger  | file_path            | Legacy  |          |           | &#10003;      |
|                | file_name            | Legacy  | &#10003; |           |               |
|                | file_dir             | Legacy  |          |           | &#10003;      |
|                | process_command_line |         |          |           |               |
|                | src_host             | Legacy  | &#10003; | &#10003;  |               |
|                | src_ip               | Legacy  | &#10003; | &#10003;  |               |
|                | src_port             | Legacy  |          |           | &#10003;      |
|                | file_ext             |         |          |           |               |
|                | additional_info      |         |          |           |               |
|                | event_code           |         |          |           |               |
|                | bytes                |         |          |           |               |
|                | dest_ip              | Legacy  | &#10003; | &#10003;  |               |
|                | hash_md5             |         |          |           |               |
|                | user_sid             |         |          |           |               |
|                | dest_port            | Legacy  |          | &#10003;  |               |
| file-delete    | src_port             |         |          |           | &#10003;      |
|                | bytes                |         |          | &#10003;  |               |
|                | hash_md5             |         |          | &#10003;  |               |
|                | src_host             | Legacy  |          | &#10003;  |               |
|                | dest_port            |         |          |           | &#10003;      |
| file-write     | src_port             |         |          |           | &#10003;      |
|                | bytes                |         |          | &#10003;  |               |
|                | hash_md5             |         |          | &#10003;  |               |
|                | src_host             |         |          | &#10003;  |               |
|                | dest_port            |         |          |           | &#10003;      |
| process-create | src_port             | Default |          |           | &#10003;      |
|                | bytes                | Default |          |           | &#10003;      |
|                | hash_md5             | Default |          |           | &#10003;      |
|                | dest_port            | Default |          |           | &#10003;      |

