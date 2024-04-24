ibm db2
=======

Expression
----------

product = ibm db2

Fields
------

| Field    | Core | Detection | Informational |
| -------- | ---- | --------- | ------------- |
| src_host |      |           | &#10003;      |
| category |      |           | &#10003;      |

Activity Types
--------------

| Activity Type   | Field              | Status  | Core     | Detection | Informational |
| --------------- | ------------------ | ------- | -------- | --------- | ------------- |
| alert-trigger   | result             |         |          |           |               |
|                 | src_ip             | Legacy  | &#10003; | &#10003;  |               |
|                 | additional_info    |         |          |           |               |
|                 | alert_id           | Legacy  |          |           | &#10003;      |
|                 | dest_ip            | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_host          | Legacy  |          | &#10003;  |               |
|                 | malware_url        |         |          |           |               |
|                 | user               | Legacy  |          | &#10003;  |               |
| database-login  | src_ip             | Default |          | &#10003;  |               |
|                 | auth_type          | Default |          |           | &#10003;      |
|                 | db_name            | Default |          |           | &#10003;      |
|                 | additional_info    | Default |          |           | &#10003;      |
|                 | process_name       | Default |          |           | &#10003;      |
|                 | event_code         | Default |          |           | &#10003;      |
|                 | db_user            | Default |          | &#10003;  |               |
|                 | event_name         | Default |          |           | &#10003;      |
|                 | operation          | Default |          |           | &#10003;      |
|                 | db_schema          | Default |          |           | &#10003;      |
|                 | object             | Default |          |           | &#10003;      |
|                 | database_user_name |         |          |           |               |
| database-modify | src_ip             | Legacy  |          |           | &#10003;      |
|                 | auth_type          |         |          |           |               |
|                 | db_name            |         |          |           |               |
|                 | event_code         |         |          |           |               |
|                 | db_user            | Legacy  |          |           | &#10003;      |
|                 | event_name         |         |          |           |               |
|                 | db_schema          |         |          |           |               |
|                 | database_user_name |         |          |           |               |
|                 | object             |         |          |           |               |
| file-read       | additional_info    |         |          |           |               |
|                 | process_name       | Legacy  |          |           | &#10003;      |
|                 | operation          |         |          |           |               |
|                 | user               | Legacy  | &#10003; | &#10003;  |               |

