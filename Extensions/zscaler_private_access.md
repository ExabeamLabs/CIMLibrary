zscaler private access
======================

Expression
----------

product = "zscaler private access"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| src_ip             |          | &#10003;  |               |
| domain             |          | &#10003;  |               |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field             | Status  | Core | Detection | Informational |
| ------------- | ----------------- | ------- | ---- | --------- | ------------- |
| vpn-login     | bytes_out         | Default |      |           | &#10003;      |
|               | bytes_in          | Default |      |           | &#10003;      |
|               | connection_status | Default |      |           | &#10003;      |
| vpn-logout    | bytes_out         | Legacy  |      | &#10003;  |               |
|               | bytes_in          |         |      | &#10003;  |               |
|               | connection_status |         |      | &#10003;  |               |

