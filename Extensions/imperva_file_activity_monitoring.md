imperva file activity monitoring
================================

Expression
----------

product = "imperva file activity monitoring"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| access_type        |      |           | &#10003;      |
| server_group       |      |           | &#10003;      |
| access             |      |           | &#10003;      |
| service_name       |      |           | &#10003;      |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| src_ip             |      | &#10003;  |               |
| src_port           |      |           | &#10003;      |
| protocol           |      |           | &#10003;      |
| domain             |      | &#10003;  |               |
| dest_ip            |      | &#10003;  |               |
| dest_host          |      | &#10003;  |               |
| user               |      | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field | Status | Core | Detection | Informational |
| ---------------------- | ----- | ------ | ---- | --------- | ------------- |
| file-delete            |       |        |      |           |               |
| file-permission-modify |       |        |      |           |               |
| file-read              |       |        |      |           |               |
| file-write             |       |        |      |           |               |

