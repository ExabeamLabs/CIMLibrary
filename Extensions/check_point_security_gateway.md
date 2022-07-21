check point security gateway
============================

Expression
----------

product = "check point security gateway"

Fields
------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| src_ip            |      | &#10003;  |               |
| src_translated_ip |      | &#10003;  |               |
| src_country_code  |      | &#10003;  |               |
| dest_ip           |      | &#10003;  |               |
| action            |      | &#10003;  |               |
| event_name        |      | &#10003;  |               |
| src_host          |      | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field                | Status  | Core | Detection | Informational |
| ------------------ | -------------------- | ------- | ---- | --------- | ------------- |
| vpn-authentication | auth_method          | Default |      |           | &#10003;      |
|                    | operating_system     | Default |      |           | &#10003;      |
| vpn-login          | user_ou              | Default |      |           | &#10003;      |
|                    | src_port             | Default |      |           | &#10003;      |
|                    | src_translated_ipnum | Default |      |           | &#10003;      |
|                    | operating_system     | Default |      |           | &#10003;      |
|                    | realm                | Default |      |           | &#10003;      |
|                    | operation            | Default |      |           | &#10003;      |
|                    | authentication_type  | Default |      |           | &#10003;      |
|                    | dest_port            | Default |      |           | &#10003;      |
|                    | direction            | Default |      |           | &#10003;      |
| vpn-logout         | user_ou              |         |      | &#10003;  |               |
|                    | dest_host            | Legacy  |      |           | &#10003;      |
|                    | session_duration     | Legacy  |      | &#10003;  |               |

