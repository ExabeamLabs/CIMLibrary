cyberark endpoint privilege manager
===================================

Expression
----------

product = "cyberark endpoint privilege manager"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| process_id      |      |           | &#10003;      |
| additional_info |      |           | &#10003;      |
| bytes           |      |           | &#10003;      |
| process_name    |      |           | &#10003;      |
| event_name      |      |           | &#10003;      |
| process_dir     |      |           | &#10003;      |
| src_host        |      |           | &#10003;      |
| process_path    |      |           | &#10003;      |
| object_id       |      |           | &#10003;      |
| policy          |      |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field                | Status | Core     | Detection | Informational |
| ------------------ | -------------------- | ------ | -------- | --------- | ------------- |
| alert-trigger      | hash_sha256          |        |          |           |               |
|                    | file_path            | Legacy |          |           | &#10003;      |
|                    | file_name            | Legacy | &#10003; |           |               |
|                    | process_name         | Legacy |          | &#10003;  |               |
|                    | file_dir             | Legacy |          |           | &#10003;      |
|                    | parent_process_name  |        |          |           |               |
|                    | dest_host            | Legacy |          | &#10003;  |               |
|                    | process_command_line |        |          |           |               |
|                    | process_path         | Legacy |          | &#10003;  |               |
|                    | user                 | Legacy |          | &#10003;  |               |
| user-privilege-use |                      |        |          |           |               |

