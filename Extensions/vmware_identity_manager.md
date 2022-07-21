vmware identity manager
=======================

Expression
----------

product = "vmware identity manager"

Fields
------

| Field                    | Core     | Detection | Informational |
| ------------------------ | -------- | --------- | ------------- |
| object_type              |          |           | &#10003;      |
| resource_type            |          |           | &#10003;      |
| device_type              |          |           | &#10003;      |
| src_host                 |          | &#10003;  |               |
| object_id                |          |           | &#10003;      |
| src_ip                   |          | &#10003;  |               |
| auth_method              |          |           | &#10003;      |
| operating_system_version |          |           | &#10003;      |
| application              |          |           | &#10003;      |
| domain                   |          | &#10003;  |               |
| object_name              |          |           | &#10003;      |
| operating_system_type    |          |           | &#10003;      |
| event_name               |          |           | &#10003;      |
| operating_system         |          |           | &#10003;      |
| user                     | &#10003; | &#10003;  |               |
| operation                |          |           | &#10003;      |
| user_agent               |          | &#10003;  |               |
| redirect_url             |          |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field           | Status  | Core | Detection | Informational |
| ------------------ | --------------- | ------- | ---- | --------- | ------------- |
| app-activity       | result          | Default |      |           | &#10003;      |
|                    | application     | Default |      |           | &#10003;      |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | user_id         | Default |      |           | &#10003;      |
| app-authentication | result          | Default |      |           | &#10003;      |
|                    | application     | Default |      |           | &#10003;      |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | user_id         | Default |      |           | &#10003;      |
| app-login          |                 |         |      |           |               |

