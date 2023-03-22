aruba clearpass policy manager
==============================

Expression
----------

product = "aruba clearpass policy manager"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      |           | &#10003;      |
| auth_type |      |           | &#10003;      |
| dest_ip   |      | &#10003;  |               |

Activity Types
--------------

| Activity Type           | Field           | Status  | Core | Detection | Informational |
| ----------------------- | --------------- | ------- | ---- | --------- | ------------- |
| endpoint-authentication | src_port        | Default |      |           | &#10003;      |
|                         | src_mac         | Default |      |           | &#10003;      |
|                         | access_type     | Default |      |           | &#10003;      |
|                         | user_type       | Default |      |           | &#10003;      |
|                         | dest_mac        | Default |      |           | &#10003;      |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | event_name      | Default |      |           | &#10003;      |
|                         | auth_server     | Default |      |           | &#10003;      |
|                         | dest_port       | Default |      |           | &#10003;      |
|                         | network         | Default |      |           | &#10003;      |
| endpoint-login          | src_port        | Default |      |           | &#10003;      |
|                         | src_mac         | Default |      |           | &#10003;      |
|                         | access_type     | Default |      |           | &#10003;      |
|                         | user_type       | Default |      |           | &#10003;      |
|                         | dest_mac        | Default |      |           | &#10003;      |
|                         | session_id      | Default |      |           | &#10003;      |
|                         | dest_port       | Default |      |           | &#10003;      |
|                         | network         | Default |      |           | &#10003;      |
| endpoint-policy-verify  | session_id      | Default |      |           | &#10003;      |

