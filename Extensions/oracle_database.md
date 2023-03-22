oracle database
===============

Expression
----------

product = "oracle db"

Fields
------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| src_ip    |          |           | &#10003;      |
| db_id     |          |           | &#10003;      |
| db_name   |          |           | &#10003;      |
| domain    |          | &#10003;  |               |
| dest_host |          |           | &#10003;      |
| src_host  |          |           | &#10003;      |
| user      | &#10003; | &#10003;  |               |
| operation |          |           | &#10003;      |
| dest_port |          |           | &#10003;      |

Activity Types
--------------

| Activity Type     | Field        | Status  | Core | Detection | Informational |
| ----------------- | ------------ | ------- | ---- | --------- | ------------- |
| database-activity | process_name | Default |      |           | &#10003;      |
|                   | service_name | Default |      |           | &#10003;      |
|                   | dest_ip      | Default |      | &#10003;  |               |
| database-delete   | db_schema    |         |      |           | &#10003;      |
|                   | db_object    |         |      |           | &#10003;      |
| database-login    | dest_user    | Default |      | &#10003;  |               |
| database-modify   | db_schema    |         |      |           | &#10003;      |
|                   | db_object    |         |      |           | &#10003;      |
| database-query    | dest_user    |         |      | &#10003;  |               |
|                   | db_schema    |         |      |           | &#10003;      |
|                   | db_object    |         |      |           | &#10003;      |

