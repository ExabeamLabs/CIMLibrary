onelogin
========

Expression
----------

product = "onelogin"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| src_ip           |      |           | &#10003;      |
| additional_info  |      |           | &#10003;      |
| event_code       |      |           | &#10003;      |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field     | Status  | Core | Detection | Informational |
| -------------------- | --------- | ------- | ---- | --------- | ------------- |
| app-activity         | dest_user | Default |      | &#10003;  |               |
| app-login            |           |         |      |           |               |
| policy-create        |           |         |      |           |               |
| policy-delete        |           |         |      |           |               |
| policy-modify        |           |         |      |           |               |
| role-create          |           |         |      |           |               |
| role-delete          |           |         |      |           |               |
| user-create          |           |         |      |           |               |
| user-delete          |           |         |      |           |               |
| user-disable         |           |         |      |           |               |
| user-enable          |           |         |      |           |               |
| user-lock            |           |         |      |           |               |
| user-modify          |           |         |      |           |               |
| user-password-modify |           |         |      |           |               |
| user-role-assign     |           |         |      |           |               |
| user-unlock          |           |         |      |           |               |

