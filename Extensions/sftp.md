sftp
====

Expression
----------

product = "sftp"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| src_ip     |      |           | &#10003;      |
| access     |      |           | &#10003;      |
| bytes      |      |           | &#10003;      |
| dest_ip    |      |           | &#10003;      |
| src_host   |      |           | &#10003;      |
| dest_port  |      |           | &#10003;      |
| user_agent |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field | Status | Core     | Detection | Informational |
| ------------- | ----- | ------ | -------- | --------- | ------------- |
| app-login     |       |        |          |           |               |
| file-delete   | user  | Legacy | &#10003; | &#10003;  |               |
| file-download | user  | Legacy | &#10003; | &#10003;  |               |
| file-read     | user  | Legacy | &#10003; | &#10003;  |               |
| file-upload   | user  | Legacy | &#10003; | &#10003;  |               |
| file-write    | user  | Legacy | &#10003; | &#10003;  |               |

