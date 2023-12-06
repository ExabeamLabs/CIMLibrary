auth0
=====

Expression
----------

product = auth0

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| src_ip           |          | &#10003;  |               |
| additional_info  |          |           | &#10003;      |
| domain           |          |           | &#10003;      |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |
| user_agent       |          |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field           | Status | Core     | Detection | Informational |
| -------------------- | --------------- | ------ | -------- | --------- | ------------- |
| alert-trigger        | app             |        |          |           |               |
|                      | src_ip          | Legacy | &#10003; | &#10003;  |               |
|                      | auth_type       |        |          |           |               |
|                      | email_address   |        |          |           |               |
|                      | additional_info |        |          |           |               |
|                      | domain          |        |          |           |               |
|                      | user_agent      |        |          |           |               |
| app-login            |                 |        |          |           |               |
| user-password-modify |                 |        |          |           |               |

