snowflake
=========

Expression
----------

product = "snowflake"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| query_id           |      |           | &#10003;      |
| db_user            |      |           | &#10003;      |
| database_user_name |      |           |               |

Activity Types
--------------

| Activity Type  | Field        | Status | Core     | Detection | Informational |
| -------------- | ------------ | ------ | -------- | --------- | ------------- |
| database-login |              |        |          |           |               |
| database-query | db_name      |        |          |           |               |
|                | db_operation | Legacy | &#10003; | &#10003;  |               |
|                | db_schema    |        |          |           |               |

