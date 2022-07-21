cyberark endpoint privilege management
======================================

Expression
----------

product = "cyberark endpoint privilege management"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field                | Status | Core     | Detection | Informational |
| ------------- | -------------------- | ------ | -------- | --------- | ------------- |
| alert-trigger | hash_sha256          |        |          |           |               |
|               | file_path            | Legacy |          |           | &#10003;      |
|               | file_name            | Legacy | &#10003; |           |               |
|               | process_name         | Legacy |          | &#10003;  |               |
|               | file_dir             | Legacy |          |           | &#10003;      |
|               | parent_process_name  |        |          |           |               |
|               | dest_host            | Legacy |          | &#10003;  |               |
|               | process_command_line |        |          |           |               |
|               | process_path         | Legacy |          | &#10003;  |               |
|               | user                 | Legacy |          | &#10003;  |               |

