synology nas
============

Expression
----------

product = "synology nas"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| src_ip           |      |           | &#10003;      |
| share_name       |      |           | &#10003;      |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field      | Status  | Core | Detection | Informational |
| ------------- | ---------- | ------- | ---- | --------- | ------------- |
| file-delete   | access     | Legacy  |      | &#10003;  |               |
|               | bytes      |         |      |           |               |
|               | bytes_unit |         |      |           |               |
| file-read     | access     | Legacy  |      | &#10003;  |               |
|               | bytes      |         |      |           |               |
|               | bytes_unit |         |      |           |               |
| file-write    | access     | Legacy  |      | &#10003;  |               |
|               | bytes      |         |      |           |               |
|               | bytes_unit |         |      |           |               |
| share-access  | protocol   | Default |      |           | &#10003;      |

