teradata rdbms
==============

Expression
----------

product = "teradata rdbms"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| src_ip     |      |           | &#10003;      |
| query_id   |      |           | &#10003;      |
| session_id |      |           | &#10003;      |
| task_id    |      |           | &#10003;      |

Activity Types
--------------

| Activity Type  | Field        | Status  | Core     | Detection | Informational |
| -------------- | ------------ | ------- | -------- | --------- | ------------- |
| database-login | db_query     | Default |          |           | &#10003;      |
|                | user         | Default |          | &#10003;  |               |
| database-query | db_name      |         |          |           |               |
|                | error_info   |         |          |           |               |
|                | db_operation | Legacy  | &#10003; | &#10003;  |               |
|                | error_code   |         |          |           |               |
|                | user         | Legacy  | &#10003; | &#10003;  |               |
|                | db_object    |         |          |           |               |

