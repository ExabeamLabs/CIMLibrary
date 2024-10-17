mssql
=====

Expression
----------

product = "mssql"

Fields
------

| Field                 | Core     | Detection | Informational |
| --------------------- | -------- | --------- | ------------- |
| service_name          |          |           | &#10003;      |
| local_user_name       |          |           |               |
| fallback_user_name    |          |           |               |
| dest_user             |          | &#10003;  |               |
| src_host              | &#10003; | &#10003;  |               |
| src_ip                |          | &#10003;  |               |
| result                |          | &#10003;  |               |
| db_name               | &#10003; | &#10003;  |               |
| dest_domain_user_name |          |           |               |
| user_id               |          |           | &#10003;      |
| event_code            |          |           | &#10003;      |
| dest_domain           |          | &#10003;  |               |
| dest_host             |          | &#10003;  |               |
| event_name            |          |           | &#10003;      |
| dest_user_id          |          |           | &#10003;      |
| user                  | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field       | Status | Core | Detection | Informational |
| --------------- | ----------- | ------ | ---- | --------- | ------------- |
| database-delete | operation   |        |      | &#10003;  |               |
| database-login  |             |        |      |           |               |
| database-query  | schema_name |        |      | &#10003;  |               |
|                 | table_name  | Legacy |      |           | &#10003;      |
|                 | operation   |        |      | &#10003;  |               |

