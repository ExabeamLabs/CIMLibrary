rangeraudit
===========

Expression
----------

product = "rangeraudit"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      | &#10003;  |               |

Activity Types
--------------

| Activity Type  | Field           | Status  | Core | Detection | Informational |
| -------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity   | application     | Default |      |           | &#10003;      |
|                | additional_info | Default |      |           | &#10003;      |
|                | resource        | Default |      |           | &#10003;      |
|                | dest_host       | Default |      | &#10003;  |               |
|                | user            | Default |      | &#10003;  |               |
|                | object          | Default |      |           | &#10003;      |
| app-login      | resource        | Default |      |           | &#10003;      |
| database-query | db_name         |         |      |           |               |
|                | resource        |         |      |           |               |
| file-read      | access          | Legacy  |      | &#10003;  |               |
|                | dest_host       | Legacy  |      | &#10003;  |               |
| file-write     | access          | Legacy  |      | &#10003;  |               |
|                | dest_host       | Legacy  |      | &#10003;  |               |

