infowatch dlp
=============

Expression
----------

product = "infowatch dlp"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| src_ip           |      | &#10003;  |               |
| domain           |      | &#10003;  |               |
| domain_user_name |      |           |               |
| user             |      | &#10003;  |               |

Activity Types
--------------

| Activity Type    | Field        | Status  | Core     | Detection | Informational |
| ---------------- | ------------ | ------- | -------- | --------- | ------------- |
| app-login        | dest_ip      | Default |          | &#10003;  |               |
| file-write       | src_host     |         |          | &#10003;  |               |
| http-session     |              |         |          |           |               |
| printer-activity | file_name    | Legacy  | &#10003; | &#10003;  |               |
|                  | dest_host    |         |          |           |               |
|                  | src_host     | Legacy  |          |           | &#10003;      |
|                  | printer_name | Legacy  | &#10003; | &#10003;  |               |

