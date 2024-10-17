rsa authentication manager
==========================

Expression
----------

product = "rsa authentication manager"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| src_ip             |          | &#10003;  |               |
| domain             |          | &#10003;  |               |
| dest_ip            |          |           | &#10003;      |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field           | Status  | Core | Detection | Informational |
| ------------------ | --------------- | ------- | ---- | --------- | ------------- |
| app-authentication | src_port        | Default |      |           | &#10003;      |
|                    | auth_method     | Default |      |           | &#10003;      |
|                    | dest_host       | Default |      | &#10003;  |               |
| app-login          | auth_method     | Default |      |           | &#10003;      |
|                    | additional_info | Default |      |           | &#10003;      |
|                    | session_id      | Default |      |           | &#10003;      |
|                    | event_name      | Default |      |           | &#10003;      |
|                    | user_agent      | Default |      |           | &#10003;      |
| user-lock          | auth_method     |         |      |           |               |
|                    | dest_host       | Legacy  |      |           | &#10003;      |

