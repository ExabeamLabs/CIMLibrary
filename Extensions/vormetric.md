vormetric
=========

Expression
----------

product = "vormetric"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| access             |      |           | &#10003;      |
| process_name       |      |           | &#10003;      |
| domain             |      |           | &#10003;      |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| process_dir        |      |           | &#10003;      |
| src_host           |      |           | &#10003;      |
| process_path       |      |           | &#10003;      |
| user               |      |           | &#10003;      |
| alert_name         |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field            | Status | Core     | Detection | Informational |
| ------------- | ---------------- | ------ | -------- | --------- | ------------- |
| alert-trigger | access           |        |          |           |               |
|               | file_name        | Legacy | &#10003; |           |               |
|               | process_name     | Legacy |          | &#10003;  |               |
|               | domain           |        |          |           |               |
|               | file_dir         | Legacy |          |           | &#10003;      |
|               | action           | Legacy |          |           | &#10003;      |
|               | dest_host        | Legacy |          | &#10003;  |               |
|               | process_dir      |        |          |           |               |
|               | domain_user_name |        |          |           |               |
|               | process_path     | Legacy |          | &#10003;  |               |
|               | user             | Legacy |          | &#10003;  |               |
| file-read     |                  |        |          |           |               |

