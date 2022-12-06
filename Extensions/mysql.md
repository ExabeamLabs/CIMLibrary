mysql
=====

Expression
----------

product = "mysql"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type     | Field         | Status  | Core | Detection | Informational |
| ----------------- | ------------- | ------- | ---- | --------- | ------------- |
| database-activity | process_id    | Default |      |           | &#10003;      |
|                   | os            | Default |      |           | &#10003;      |
|                   | db_query      | Default |      |           | &#10003;      |
|                   | db_name       | Default |      |           | &#10003;      |
|                   | dest_ip       | Default |      | &#10003;  |               |
|                   | dest_host     | Default |      | &#10003;  |               |
|                   | dest_user     | Default |      | &#10003;  |               |
|                   | user          | Default |      | &#10003;  |               |
|                   | response_size | Default |      |           | &#10003;      |
|                   | db_object     | Default |      |           | &#10003;      |
| database-query    | src_ip        | Legacy  |      | &#10003;  |               |
|                   | src_host      | Legacy  |      | &#10003;  |               |
|                   | table_name    | Legacy  |      |           | &#10003;      |
|                   | db_schema     |         |      |           |               |
|                   | operation     |         |      |           |               |

