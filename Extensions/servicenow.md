servicenow
==========

Expression
----------

product = "servicenow"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| src_ip     |      |           | &#10003;      |
| resource   |      |           | &#10003;      |
| event_name |      |           | &#10003;      |
| object     |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field            | Status  | Core     | Detection | Informational |
| ------------- | ---------------- | ------- | -------- | --------- | ------------- |
| app-activity  | app              | Default |          |           | &#10003;      |
|               | file_path        | Default |          |           | &#10003;      |
|               | file_name        | Default |          |           | &#10003;      |
|               | domain_user_name |         |          |           |               |
|               | table_name       | Default |          |           | &#10003;      |
|               | dproc            | Default |          |           | &#10003;      |
|               | file_ext         | Default |          |           | &#10003;      |
|               | additional_info  | Default |          |           | &#10003;      |
|               | bytes            | Default |          |           | &#10003;      |
|               | file_type        | Default |          |           | &#10003;      |
|               | domain           | Default |          |           | &#10003;      |
|               | event_name       | Default |          |           | &#10003;      |
|               | user             | Default |          | &#10003;  |               |
|               | new_value        | Default |          |           | &#10003;      |
|               | table            | Default |          |           | &#10003;      |
| app-login     |                  |         |          |           |               |
| file-delete   | bytes            |         |          |           |               |
|               | file_type        | Legacy  |          |           | &#10003;      |
|               | domain           |         |          |           |               |
|               | action           |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | old_value        |         |          |           |               |
|               | user             | Legacy  | &#10003; | &#10003;  |               |
|               | operation        |         |          |           |               |
|               | table_name       |         |          |           |               |
|               | table            |         |          |           |               |
|               | new_value        |         |          |           |               |
|               | dproc            |         |          |           |               |
| file-download | bytes            | Legacy  |          | &#10003;  |               |
|               | file_type        | Legacy  |          |           | &#10003;      |
|               | domain           |         |          |           |               |
|               | action           |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | old_value        |         |          |           |               |
|               | user             | Legacy  | &#10003; | &#10003;  |               |
|               | operation        |         |          |           |               |
|               | table_name       |         |          |           |               |
|               | table            |         |          |           |               |
|               | new_value        |         |          |           |               |
|               | dproc            |         |          |           |               |
| file-read     | bytes            | Legacy  |          |           | &#10003;      |
|               | file_type        | Legacy  |          |           | &#10003;      |
|               | domain           |         |          |           |               |
|               | action           |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | old_value        |         |          |           |               |
|               | user             | Legacy  | &#10003; | &#10003;  |               |
|               | operation        |         |          |           |               |
|               | table_name       |         |          |           |               |
|               | table            |         |          |           |               |
|               | new_value        |         |          |           |               |
|               | dproc            |         |          |           |               |
| file-upload   | bytes            |         |          |           |               |
|               | file_type        | Legacy  |          |           | &#10003;      |
|               | domain           |         |          |           |               |
|               | action           |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | old_value        |         |          |           |               |
|               | user             | Legacy  | &#10003; | &#10003;  |               |
|               | operation        |         |          |           |               |
|               | table_name       |         |          |           |               |
|               | table            |         |          |           |               |
|               | new_value        |         |          |           |               |
|               | dproc            |         |          |           |               |

