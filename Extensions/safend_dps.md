safend dps
==========

Expression
----------

product = "safend dps"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |
| operation        |          |           | &#10003;      |

Activity Types
--------------

| Activity Type               | Field       | Status | Core | Detection | Informational |
| --------------------------- | ----------- | ------ | ---- | --------- | ------------- |
| file-read                   | device_id   | Legacy |      | &#10003;  |               |
|                             | os          |        |      | &#10003;  |               |
|                             | bytes_out   |        |      |           | &#10003;      |
|                             | device_type | Legacy |      |           | &#10003;      |
| file-write                  | device_id   | Legacy |      | &#10003;  |               |
|                             | os          |        |      |           | &#10003;      |
|                             | bytes_in    |        |      | &#10003;  |               |
|                             | device_type | Legacy |      |           | &#10003;      |
| peripheral_storage-activity |             |        |      |           |               |

