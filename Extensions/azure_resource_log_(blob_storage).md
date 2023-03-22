azure resource log (blob storage)
=================================

Expression
----------

product = "azure resource log (blob storage)"

Fields
------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| tenant_id         |      |           | &#10003;      |
| auth_type         |      |           | &#10003;      |
| operation_version |      |           | &#10003;      |
| operation_type    |      |           | &#10003;      |
| bytes_in          |      | &#10003;  |               |
| event_category    |      |           | &#10003;      |
| url               |      |           | &#10003;      |
| result            |      |           | &#10003;      |
| src_ip            |      | &#10003;  |               |
| schema_version    |      |           | &#10003;      |
| referrer          |      |           | &#10003;      |
| time_modified     |      |           | &#10003;      |
| protocol          |      |           | &#10003;      |
| bytes_out         |      | &#10003;  |               |
| domain            |      |           | &#10003;      |
| correlation_id    |      |           | &#10003;      |
| result_code       |      |           | &#10003;      |
| storage_account   |      | &#10003;  |               |
| region            |      | &#10003;  |               |
| operation         |      | &#10003;  |               |
| user              |      | &#10003;  |               |
| user_agent        |      | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field | Status | Core | Detection | Informational |
| ---------------------- | ----- | ------ | ---- | --------- | ------------- |
| file-list              |       |        |      |           |               |
| file-permission-modify |       |        |      |           |               |
| file-read              |       |        |      |           |               |
| file-write             |       |        |      |           |               |

