postgresql
==========

Expression
----------

product = "postgresql"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ip             |      |           | &#10003;      |
| db_name            |      |           | &#10003;      |
| additional_info    |      |           | &#10003;      |
| db_user            |      |           | &#10003;      |
| alert_id           |      |           | &#10003;      |
| event_name         |      |           | &#10003;      |
| src_host           |      |           | &#10003;      |
| dtz                |      |           | &#10003;      |
| database_user_name |      |           |               |

Activity Types
--------------

| Activity Type     | Field          | Status  | Core     | Detection | Informational |
| ----------------- | -------------- | ------- | -------- | --------- | ------------- |
| database-activity | user           | Default |          | &#10003;  |               |
| database-delete   | user           | Legacy  | &#10003; |           |               |
| database-login    |                |         |          |           |               |
| database-query    | src_port       |         |          |           |               |
|                   | transaction_id |         |          |           |               |
|                   | severity       |         |          |           |               |
|                   | process_id     |         |          |           |               |
|                   | object_type    |         |          |           |               |
|                   | dest_ip        |         |          |           |               |
|                   | session_id     |         |          |           |               |
|                   | dest_host      | Legacy  |          |           | &#10003;      |
|                   | user           | Legacy  | &#10003; | &#10003;  |               |
|                   | operation      |         |          |           |               |
|                   | db_object      |         |          |           |               |

