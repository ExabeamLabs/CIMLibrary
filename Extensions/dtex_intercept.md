dtex intercept
==============

Expression
----------

product = "dtex intercept"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| domain             |          |           | &#10003;      |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type    | Field        | Status  | Core     | Detection | Informational |
| ---------------- | ------------ | ------- | -------- | --------- | ------------- |
| endpoint-lock    | event_code   |         |          |           | &#10003;      |
| endpoint-login   | event_code   | Default |          |           | &#10003;      |
| endpoint-unlock  | event_code   | Legacy  |          |           | &#10003;      |
| file-delete      | access       | Legacy  |          | &#10003;  |               |
|                  | process_name | Legacy  |          |           | &#10003;      |
|                  | bytes        |         |          |           | &#10003;      |
|                  | process_dir  | Legacy  |          |           | &#10003;      |
| file-read        | access       | Legacy  |          | &#10003;  |               |
|                  | process_name | Legacy  |          |           | &#10003;      |
|                  | bytes        | Legacy  |          |           | &#10003;      |
|                  | process_dir  | Legacy  |          |           | &#10003;      |
| file-write       | access       | Legacy  |          | &#10003;  |               |
|                  | process_name | Legacy  |          |           | &#10003;      |
|                  | bytes        | Legacy  |          | &#10003;  |               |
|                  | process_dir  | Legacy  |          |           | &#10003;      |
| http-session     | os           | Default |          |           | &#10003;      |
| printer-activity | bytes        | Legacy  |          | &#10003;  |               |
|                  | num_pages    | Legacy  |          | &#10003;  |               |
|                  | printer_name | Legacy  | &#10003; | &#10003;  |               |
| process-create   |              |         |          |           |               |

