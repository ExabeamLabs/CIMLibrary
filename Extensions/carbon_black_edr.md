carbon black edr
================

Expression
----------

product = "carbon black edr"

Fields
------

| Field                | Core     | Detection | Informational |
| -------------------- | -------- | --------- | ------------- |
| process_id           |          |           | &#10003;      |
| device_id            |          |           | &#10003;      |
| process_dir          |          | &#10003;  |               |
| fallback_user_name   |          |           |               |
| domain_user_name     |          |           |               |
| src_host             |          | &#10003;  |               |
| process_command_line |          | &#10003;  |               |
| process_guid         |          |           | &#10003;      |
| process_name         |          | &#10003;  |               |
| alert_id             |          |           | &#10003;      |
| dest_ip              | &#10003; | &#10003;  |               |
| domain               |          | &#10003;  |               |
| parent_process_guid  |          |           | &#10003;      |
| process_path         |          | &#10003;  |               |
| user                 |          | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field                       | Status  | Core | Detection | Informational |
| --------------- | --------------------------- | ------- | ---- | --------- | ------------- |
| file-write      | parent_process_id           |         |      |           | &#10003;      |
|                 | parent_process_command_line |         |      | &#10003;  |               |
|                 | parent_process_name         |         |      | &#10003;  |               |
|                 | parent_process_dir          |         |      | &#10003;  |               |
|                 | parent_process_path         |         |      | &#10003;  |               |
| network-session | parent_process_id           | Default |      |           | &#10003;      |
|                 | parent_process_command_line | Default |      |           | &#10003;      |
|                 | parent_process_name         | Default |      |           | &#10003;      |
|                 | parent_process_dir          | Default |      |           | &#10003;      |
|                 | parent_process_path         | Default |      |           | &#10003;      |
| process-create  | sensor_id                   | Default |      |           | &#10003;      |
|                 | device_id                   | Default |      |           | &#10003;      |
|                 | domain                      | Default |      |           | &#10003;      |
|                 | hash_md5                    | Default |      |           | &#10003;      |
|                 | dest_host                   | Default |      | &#10003;  |               |
|                 | parent_process_guid         | Default |      |           | &#10003;      |
|                 | domain_user_name            |         |      |           |               |
|                 | process_command_line        | Default |      |           | &#10003;      |
|                 | user                        | Default |      | &#10003;  |               |

