cassandra
=========

Expression
----------

product = "cassandra"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type     | Field           | Status  | Core | Detection | Informational |
| ----------------- | --------------- | ------- | ---- | --------- | ------------- |
| database-activity | src_ip          | Default |      | &#10003;  |               |
|                   | additional_info | Default |      |           | &#10003;      |
|                   | dest_ip         | Default |      | &#10003;  |               |
|                   | event_name      | Default |      |           | &#10003;      |
|                   | dest_user       | Default |      | &#10003;  |               |
| database-login    | src_ip          | Default |      | &#10003;  |               |
|                   | additional_info | Default |      |           | &#10003;      |
|                   | dest_ip         | Default |      | &#10003;  |               |
|                   | event_name      | Default |      |           | &#10003;      |
|                   | dest_user       | Default |      | &#10003;  |               |
| database-modify   | src_ip          | Legacy  |      |           | &#10003;      |
|                   | db_name         |         |      |           |               |
|                   | additional_info |         |      |           |               |
|                   | dest_ip         |         |      |           |               |
|                   | dest_user       |         |      |           |               |

