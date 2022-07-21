event viewer - system
=====================

Expression
----------

product = "event viewer - system"

Fields
------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| log_name   |          |           | &#10003;      |
| event_code |          |           | &#10003;      |
| domain     |          | &#10003;  |               |
| event_name |          |           | &#10003;      |
| dest_host  | &#10003; | &#10003;  |               |
| user       | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type  | Field                | Status | Core | Detection | Informational |
| -------------- | -------------------- | ------ | ---- | --------- | ------------- |
| service-create | file_path            |        |      |           |               |
|                | service_command_line |        |      |           |               |
|                | service_type         |        |      |           |               |
|                | file_ext             |        |      |           |               |
|                | file_name            |        |      |           |               |
|                | file_dir             |        |      |           |               |
|                | dest_domain          |        |      |           |               |
|                | service_start_type   | Legacy |      |           | &#10003;      |
|                | dest_user            |        |      |           |               |

