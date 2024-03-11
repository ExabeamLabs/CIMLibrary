duo access security
===================

Expression
----------

product = "duo access security"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| result           |      |           | &#10003;      |
| src_ip           |      | &#10003;  |               |
| os               |      |           | &#10003;      |
| location_country |      |           | &#10003;      |
| location_city    |      |           | &#10003;      |
| location_state   |      |           | &#10003;      |
| user_agent       |      |           | &#10003;      |
| object           |      |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field           | Status  | Core     | Detection | Informational |
| ------------------ | --------------- | ------- | -------- | --------- | ------------- |
| app-activity       | auth_method     | Default |          |           | &#10003;      |
|                    | domain          | Default |          |           | &#10003;      |
|                    | user            | Default | &#10003; | &#10003;  |               |
| app-authentication | new_enrollment  | Default |          |           | &#10003;      |
|                    | session_id      | Default |          |           | &#10003;      |
| app-login          | additional_info | Default |          |           | &#10003;      |
| user-create        | additional_info |         |          |           | &#10003;      |
|                    | factor          |         |          |           | &#10003;      |
|                    | alert_type      |         |          |           | &#10003;      |
| vpn-login          | additional_info | Default |          |           | &#10003;      |
|                    | service_name    | Default |          |           | &#10003;      |

