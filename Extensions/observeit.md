observeit
=========

Expression
----------

product = "observeit"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| src_ip             |          | &#10003;  |               |
| os                 |          |           | &#10003;      |
| domain             |          | &#10003;  |               |
| session_id         |          |           | &#10003;      |
| dest_host          |          | &#10003;  |               |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type     | Field                | Status  | Core     | Detection | Informational |
| ----------------- | -------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger     | src_ip               | Legacy  | &#10003; | &#10003;  |               |
|                   | os                   |         |          |           |               |
|                   | additional_info      |         |          |           |               |
|                   | process_name         | Legacy  |          | &#10003;  |               |
|                   | alert_id             | Legacy  |          |           | &#10003;      |
|                   | domain               |         |          |           |               |
|                   | dest_host            | Legacy  |          | &#10003;  |               |
|                   | session_id           |         |          |           |               |
|                   | domain_user_name     |         |          |           |               |
|                   | src_host             | Legacy  | &#10003; | &#10003;  |               |
|                   | user                 | Legacy  |          | &#10003;  |               |
|                   | target               |         |          |           |               |
| app-activity      | additional_info      | Default |          |           | &#10003;      |
|                   | dest_ip              | Default |          | &#10003;  |               |
|                   | src_host             | Default |          | &#10003;  |               |
|                   | object               | Default |          |           | &#10003;      |
| app-login         |                      |         |          |           |               |
| database-activity | dest_local_user_name |         |          |           |               |
|                   | db_name              | Default |          |           | &#10003;      |
|                   | process_name         | Default |          |           | &#10003;      |
|                   | dest_user            | Default |          | &#10003;  |               |
|                   | src_host             | Default |          | &#10003;  |               |
|                   | db_object            | Default |          |           | &#10003;      |
| endpoint-login    |                      |         |          |           |               |
| process-create    |                      |         |          |           |               |

