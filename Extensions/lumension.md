lumension
=========

Expression
----------

product = "lumension"

Fields
------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| device_id         |      |           | &#10003;      |
| user_id           |      |           | &#10003;      |
| bytes             |      |           | &#10003;      |
| domain            |      |           | &#10003;      |
| device_type       |      |           | &#10003;      |
| domain_user_name  |      |           |               |
| user              |      |           | &#10003;      |
| operation_details |      |           | &#10003;      |
| operation         |      |           | &#10003;      |

Activity Types
--------------

| Activity Type               | Field     | Status  | Core | Detection | Informational |
| --------------------------- | --------- | ------- | ---- | --------- | ------------- |
| file-read                   |           |         |      |           |               |
| file-write                  |           |         |      |           |               |
| peripheral_storage-activity | file_path | Default |      |           | &#10003;      |
|                             | file_ext  | Default |      |           | &#10003;      |
|                             | file_name | Default |      |           | &#10003;      |
| peripheral_storage-insert   | file_path |         |      |           |               |
|                             | file_ext  |         |      |           |               |
|                             | file_name |         |      |           |               |

