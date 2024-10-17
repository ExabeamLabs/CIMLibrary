mastersam pam
=============

Expression
----------

product = "mastersam pam"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| protocol           |      |           | &#10003;      |
| domain             |      |           | &#10003;      |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| user               |      | &#10003;  |               |

Activity Types
--------------

| Activity Type           | Field    | Status  | Core | Detection | Informational |
| ----------------------- | -------- | ------- | ---- | --------- | ------------- |
| endpoint-authentication | dest_ip  | Default |      | &#10003;  |               |
| endpoint-login          | dest_ip  | Default |      | &#10003;  |               |
| user-password-reset     | src_ip   |         |      |           |               |
|                         | src_host |         |      |           |               |

