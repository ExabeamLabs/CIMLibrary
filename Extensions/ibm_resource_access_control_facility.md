ibm resource access control facility
====================================

Expression
----------

product = "ibm racf"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| additional_info    |      |           | &#10003;      |
| dest_ip            |      |           | &#10003;      |
| db_user            |      |           | &#10003;      |
| user               |      |           | &#10003;      |
| database_user_name |      |           |               |
| object             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type     | Field                 | Status  | Core | Detection | Informational |
| ----------------- | --------------------- | ------- | ---- | --------- | ------------- |
| app-activity      | identifier            | Default |      |           | &#10003;      |
|                   | group_name            | Default |      |           | &#10003;      |
|                   | dest_user             | Default |      | &#10003;  |               |
|                   | terminal              | Default |      |           | &#10003;      |
|                   | src_host              | Default |      | &#10003;  |               |
|                   | alert_type            | Default |      |           | &#10003;      |
|                   | manager_name          | Default |      |           | &#10003;      |
|                   | environment           | Default |      |           | &#10003;      |
|                   | dest_domain_user_name |         |      |           |               |
|                   | user_id               | Default |      |           | &#10003;      |
|                   | additional_info       | Default |      |           | &#10003;      |
|                   | event_code            | Default |      |           | &#10003;      |
|                   | process_name          | Default |      |           | &#10003;      |
|                   | domain                | Default |      |           | &#10003;      |
|                   | dest_host             | Default |      | &#10003;  |               |
|                   | manager_email         | Default |      |           | &#10003;      |
| app-login         | manager_name          | Default |      |           | &#10003;      |
|                   | identifier            | Default |      |           | &#10003;      |
|                   | environment           | Default |      |           | &#10003;      |
|                   | manager               | Default |      |           | &#10003;      |
|                   | user_id               | Default |      |           | &#10003;      |
|                   | group_name            | Default |      |           | &#10003;      |
|                   | process_name          | Default |      |           | &#10003;      |
|                   | dest_host             | Default |      | &#10003;  |               |
|                   | src_host              | Default |      | &#10003;  |               |
|                   | terminal              | Default |      |           | &#10003;      |
|                   | operation             | Default |      |           | &#10003;      |
|                   | alert_type            | Default |      |           | &#10003;      |
| database-activity | event_name            | Default |      |           | &#10003;      |
|                   | command               | Default |      |           | &#10003;      |

