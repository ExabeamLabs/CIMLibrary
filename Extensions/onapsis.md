onapsis
=======

Expression
----------

product = "onapsis"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type   | Field           | Status  | Core     | Detection | Informational |
| --------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-login       | src_port        | Default |          |           | &#10003;      |
|                 | protocol        | Default |          |           | &#10003;      |
|                 | dest_ip         | Default |          | &#10003;  |               |
|                 | dest_host       | Default |          | &#10003;  |               |
|                 | event_name      | Default |          |           | &#10003;      |
|                 | src_host        | Default |          | &#10003;  |               |
|                 | tag             | Default |          |           | &#10003;      |
|                 | category        | Default |          |           | &#10003;      |
|                 | dest_port       | Default |          |           | &#10003;      |
| database-modify | additional_info |         |          |           |               |
|                 | user_id         |         |          |           |               |
|                 | alert_id        |         |          |           |               |
|                 | user            | Legacy  | &#10003; |           |               |
|                 | table_name      | Legacy  |          |           | &#10003;      |
|                 | operation       |         |          |           |               |

