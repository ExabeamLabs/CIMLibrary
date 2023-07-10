workday
=======

Expression
----------

product = "workday"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| src_ip           |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field           | Status  | Core | Detection | Informational |
| ------------------ | --------------- | ------- | ---- | --------- | ------------- |
| app-activity       | src_ip          | Default |      | &#10003;  |               |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | device_type     | Default |      |           | &#10003;      |
|                    | user_agent      | Default |      |           | &#10003;      |
|                    | object          | Default |      |           | &#10003;      |
| app-authentication | auth_method     | Default |      |           | &#10003;      |
|                    | dest_ip         | Default |      | &#10003;  |               |
| app-login          | src_ip          | Default |      | &#10003;  |               |
|                    | device_type     | Default |      |           | &#10003;      |
|                    | user_agent      | Default |      |           | &#10003;      |

