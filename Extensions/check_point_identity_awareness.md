check point identity awareness
==============================

Expression
----------

product = "check point identity awareness"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      | &#10003;  |               |
| src_port  |      | &#10003;  |               |
| protocol  |      | &#10003;  |               |
| event_id  |      |           | &#10003;      |
| log_uid   |      |           | &#10003;      |
| dest_ip   |      | &#10003;  |               |
| action    |      | &#10003;  |               |
| dest_port |      | &#10003;  |               |
| origin_ip |      | &#10003;  |               |
| direction |      | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field            | Status  | Core     | Detection | Informational |
| --------------- | ---------------- | ------- | -------- | --------- | ------------- |
| network-traffic | src_interface    | Default |          |           | &#10003;      |
|                 | user             | Default | &#10003; | &#10003;  |               |
|                 | user_uid         | Default |          |           | &#10003;      |
| vpn-login       | user_ou          | Default |          |           | &#10003;      |
|                 | auth_method      | Default |          |           | &#10003;      |
|                 | additional_info  | Default |          |           | &#10003;      |
|                 | dest_host        | Default |          | &#10003;  |               |
|                 | src_host         | Default |          | &#10003;  |               |
|                 | user_group_name  | Default |          |           | &#10003;      |
|                 | operation        | Default |          |           | &#10003;      |
|                 | session_duration | Default |          |           | &#10003;      |
| vpn-logout      | user_ou          |         |          | &#10003;  |               |
|                 | auth_method      |         |          | &#10003;  |               |
|                 | additional_info  |         |          |           | &#10003;      |
|                 | dest_host        | Legacy  |          |           | &#10003;      |
|                 | src_host         |         |          | &#10003;  |               |
|                 | user_group_name  |         |          | &#10003;  |               |
|                 | operation        |         |          | &#10003;  |               |
|                 | session_duration | Legacy  |          | &#10003;  |               |

