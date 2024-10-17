juniper pulse secure
====================

Expression
----------

product = "juniper pulse secure"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ip             |      | &#10003;  |               |
| domain             |      | &#10003;  |               |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| user               |      | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field            | Status  | Core | Detection | Informational |
| ------------------ | ---------------- | ------- | ---- | --------- | ------------- |
| app-activity       | bytes            | Default |      |           | &#10003;      |
|                    | dest_ip          | Default |      | &#10003;  |               |
|                    | dest_host        | Default |      | &#10003;  |               |
|                    | src_host         | Default |      | &#10003;  |               |
|                    | user_agent       | Default |      |           | &#10003;      |
| http-request       | app              | Default |      |           | &#10003;      |
|                    | additional_info  | Default |      |           | &#10003;      |
|                    | bytes            | Default |      |           | &#10003;      |
|                    | dest_host        | Default |      | &#10003;  |               |
|                    | operation        | Default |      |           | &#10003;      |
| http-session       | role             | Default |      |           | &#10003;      |
|                    | firewall         | Default |      |           | &#10003;      |
|                    | realm            | Default |      |           | &#10003;      |
| user-delete        | role             |         |      |           | &#10003;      |
|                    | realm            |         |      |           | &#10003;      |
| vpn-authentication | dest_ip          | Default |      | &#10003;  |               |
|                    | dest_host        | Default |      | &#10003;  |               |
| vpn-login          | dest_ip          | Default |      | &#10003;  |               |
|                    | dest_host        | Default |      | &#10003;  |               |
| vpn-logout         | src_port         |         |      | &#10003;  |               |
|                    | bytes_out        | Legacy  |      | &#10003;  |               |
|                    | bytes_in         |         |      | &#10003;  |               |
|                    | dest_ip          |         |      | &#10003;  |               |
|                    | dest_host        | Legacy  |      |           | &#10003;      |
|                    | session_duration | Legacy  |      | &#10003;  |               |
|                    | dest_port        |         |      | &#10003;  |               |

