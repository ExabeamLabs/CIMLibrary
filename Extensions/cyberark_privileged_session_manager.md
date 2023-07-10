cyberark privileged session manager
===================================

Expression
----------

product = "cyberark psm"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type      | Field            | Status  | Core     | Detection | Informational |
| ------------------ | ---------------- | ------- | -------- | --------- | ------------- |
| app-activity       | additional_info  | Default |          |           | &#10003;      |
|                    | app_group        | Default |          |           | &#10003;      |
|                    | event_subtype    | Default |          |           | &#10003;      |
|                    | user             | Default |          | &#10003;  |               |
| app-login          | src_ip           | Default |          | &#10003;  |               |
|                    | protocol         | Default |          |           | &#10003;      |
|                    | event_code       | Default |          |           | &#10003;      |
|                    | event_subtype    | Default |          |           | &#10003;      |
|                    | url              | Default |          |           | &#10003;      |
| user-password-read | event_code       | Legacy  |          |           | &#10003;      |
|                    | domain           | Legacy  |          |           | &#10003;      |
|                    | domain_user_name |         |          |           |               |
|                    | user             | Legacy  | &#10003; |           |               |

