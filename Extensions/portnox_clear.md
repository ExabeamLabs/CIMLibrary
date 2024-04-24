portnox clear
=============

Expression
----------

product = "portnox clear"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| src_ip          |      |           | &#10003;      |
| auth_method     |      |           | &#10003;      |
| additional_info |      |           | &#10003;      |
| event_code      |      |           | &#10003;      |
| dest_ip         |      |           | &#10003;      |
| event_name      |      |           | &#10003;      |
| policy          |      |           | &#10003;      |

Activity Types
--------------

| Activity Type           | Field            | Status  | Core | Detection | Informational |
| ----------------------- | ---------------- | ------- | ---- | --------- | ------------- |
| endpoint-authentication |                  |         |      |           |               |
| endpoint-policy-verify  | domain           | Default |      |           | &#10003;      |
|                         | domain_user_name |         |      |           |               |
|                         | user             | Default |      | &#10003;  |               |

