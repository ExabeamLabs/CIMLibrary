imperva securesphere
====================

Expression
----------

product = imperva securesphere

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      | &#10003;  |               |
| domain    |      | &#10003;  |               |
| dest_ip   |      | &#10003;  |               |
| dest_host |      |           | &#10003;      |
| src_host  |      |           | &#10003;      |
| user      |      | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field           | Status  | Core     | Detection | Informational |
| --------------- | --------------- | ------- | -------- | --------- | ------------- |
| alert-trigger   | app             |         |          |           |               |
|                 | server_group    |         |          |           |               |
|                 | service_name    |         |          |           |               |
|                 | src_host        | Legacy  | &#10003; | &#10003;  |               |
|                 | src_ip          | Legacy  | &#10003; | &#10003;  |               |
|                 | src_port        | Legacy  |          |           | &#10003;      |
|                 | db_name         |         |          |           |               |
|                 | additional_info |         |          |           |               |
|                 | alert_id        | Legacy  |          |           | &#10003;      |
|                 | dest_ip         | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_host       | Legacy  |          | &#10003;  |               |
|                 | user            | Legacy  |          | &#10003;  |               |
|                 | db_schema       |         |          |           |               |
| database-delete | src_port        |         |          |           |               |
|                 | db_name         |         |          |           |               |
|                 | service_name    |         |          |           |               |
|                 | operation       |         |          |           |               |
|                 | dest_port       |         |          |           |               |
| database-login  | src_port        | Default |          |           | &#10003;      |
|                 | server_group    | Default |          |           | &#10003;      |
|                 | protocol        | Default |          |           | &#10003;      |
|                 | db_name         | Default |          |           | &#10003;      |
|                 | service_name    | Default |          |           | &#10003;      |
|                 | db_schema       | Default |          |           | &#10003;      |
|                 | dest_port       | Default |          |           | &#10003;      |
| database-modify | src_port        |         |          |           |               |
|                 | server_group    |         |          |           |               |
|                 | bytes_out       |         |          |           |               |
|                 | db_name         |         |          |           |               |
|                 | service_name    |         |          |           |               |
|                 | operation       |         |          |           |               |
|                 | db_schema       |         |          |           |               |
|                 | dest_port       |         |          |           |               |
| database-query  | src_port        |         |          |           |               |
|                 | server_group    |         |          |           |               |
|                 | bytes_out       |         |          |           |               |
|                 | db_name         |         |          |           |               |
|                 | service_name    |         |          |           |               |
|                 | operation       |         |          |           |               |
|                 | db_schema       |         |          |           |               |
|                 | dest_port       |         |          |           |               |

