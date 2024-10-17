vmware identity manager
=======================

Expression
----------

product = "vmware identity manager"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| app                |          |           | &#10003;      |
| os                 |          |           | &#10003;      |
| object_type        |          |           | &#10003;      |
| os_version         |          |           | &#10003;      |
| resource_type      |          |           | &#10003;      |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| device_type        |          |           | &#10003;      |
| src_host           |          | &#10003;  |               |
| object_id          |          |           | &#10003;      |
| src_ip             |          | &#10003;  |               |
| auth_method        |          |           | &#10003;      |
| domain             |          | &#10003;  |               |
| object_name        |          |           | &#10003;      |
| os_type            |          |           | &#10003;      |
| event_name         |          |           | &#10003;      |
| user               | &#10003; | &#10003;  |               |
| operation          |          |           | &#10003;      |
| user_agent         |          | &#10003;  |               |
| redirect_url       |          |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field           | Status  | Core | Detection | Informational |
| ------------------ | --------------- | ------- | ---- | --------- | ------------- |
| app-activity       | app             | Default |      |           | &#10003;      |
|                    | result          | Default |      |           | &#10003;      |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | user_id         | Default |      |           | &#10003;      |
| app-authentication | app             | Default |      |           | &#10003;      |
|                    | result          | Default |      |           | &#10003;      |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | user_id         | Default |      |           | &#10003;      |
| app-login          |                 |         |      |           |               |

