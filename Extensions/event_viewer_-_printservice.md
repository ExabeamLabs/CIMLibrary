event viewer - printservice
===========================

Expression
----------

product = "event viewer - printservice"

Fields
------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| log_name   |          |           | &#10003;      |
| event_code |          |           | &#10003;      |
| domain     |          | &#10003;  |               |
| dest_host  | &#10003; | &#10003;  |               |
| event_name |          |           | &#10003;      |
| user       | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type    | Field        | Status | Core     | Detection | Informational |
| ---------------- | ------------ | ------ | -------- | --------- | ------------- |
| printer-activity | file_path    |        |          | &#10003;  |               |
|                  | file_ext     |        |          | &#10003;  |               |
|                  | bytes_out    |        |          | &#10003;  |               |
|                  | file_name    | Legacy | &#10003; | &#10003;  |               |
|                  | file_dir     |        |          | &#10003;  |               |
|                  | num_pages    | Legacy |          | &#10003;  |               |
|                  | printer_port |        |          | &#10003;  |               |
|                  | printer_name | Legacy | &#10003; | &#10003;  |               |

