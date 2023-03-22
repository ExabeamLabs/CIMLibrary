mariadb
=======

Expression
----------

product = "mariadb"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type     | Field         | Status  | Core     | Detection | Informational |
| ----------------- | ------------- | ------- | -------- | --------- | ------------- |
| database-activity | src_ip        | Default |          | &#10003;  |               |
|                   | query_id      | Default |          |           | &#10003;      |
|                   | db_name       | Default |          |           | &#10003;      |
|                   | connection_id | Default |          |           | &#10003;      |
|                   | user          | Default |          | &#10003;  |               |
|                   | object        | Default |          |           | &#10003;      |
| database-delete   | src_ip        | Legacy  |          |           | &#10003;      |
|                   | query_id      |         |          |           |               |
|                   | db_name       |         |          |           |               |
|                   | connection_id |         |          |           |               |
|                   | user          | Legacy  | &#10003; |           |               |
|                   | operation     |         |          |           |               |
|                   | object        |         |          |           |               |
| database-login    | src_ip        | Default |          | &#10003;  |               |
|                   | query_id      | Default |          |           | &#10003;      |
|                   | db_name       | Default |          |           | &#10003;      |
|                   | connection_id | Default |          |           | &#10003;      |
|                   | operation     | Default |          |           | &#10003;      |
|                   | object        | Default |          |           | &#10003;      |
| database-modify   | src_ip        | Legacy  |          |           | &#10003;      |
|                   | query_id      |         |          |           |               |
|                   | db_name       |         |          |           |               |
|                   | connection_id |         |          |           |               |
|                   | user          | Legacy  | &#10003; |           |               |
|                   | operation     |         |          |           |               |
|                   | object        |         |          |           |               |
| database-query    | src_ip        | Legacy  |          | &#10003;  |               |
|                   | query_id      |         |          |           |               |
|                   | db_name       |         |          |           |               |
|                   | connection_id |         |          |           |               |
|                   | user          | Legacy  | &#10003; | &#10003;  |               |
|                   | operation     |         |          |           |               |
|                   | object        |         |          |           |               |

