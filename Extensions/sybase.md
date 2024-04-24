sybase
======

Expression
----------

product = "sybase"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| db_name            |      |           | &#10003;      |
| additional_info    |      |           | &#10003;      |
| db_user            |      |           | &#10003;      |
| db_object          |      |           | &#10003;      |
| database_user_name |      |           |               |

Activity Types
--------------

| Activity Type     | Field        | Status  | Core     | Detection | Informational |
| ----------------- | ------------ | ------- | -------- | --------- | ------------- |
| database-activity | dest_ip      | Default |          | &#10003;  |               |
|                   | dest_host    | Default |          | &#10003;  |               |
|                   | db_operation | Default |          |           | &#10003;      |
|                   | user         | Default |          | &#10003;  |               |
| database-login    | src_ip       | Default |          | &#10003;  |               |
|                   | dest_ip      | Default |          | &#10003;  |               |
|                   | dest_host    | Default |          | &#10003;  |               |
|                   | src_host     | Default |          | &#10003;  |               |
| database-query    | dest_ip      |         |          |           |               |
|                   | dest_host    | Legacy  |          |           | &#10003;      |
|                   | db_operation | Legacy  | &#10003; | &#10003;  |               |
|                   | user         | Legacy  | &#10003; | &#10003;  |               |

