kiteworks
=========

Expression
----------

product = "kiteworks"

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

| Activity Type          | Field           | Status  | Core | Detection | Informational |
| ---------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity           | access          | Default |      |           | &#10003;      |
|                        | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
| app-login              | access          | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
| configuration-modify   | additional_info |         |      |           |               |
|                        | mime            |         |      |           |               |
|                        | operation       |         |      |           |               |
|                        | url             |         |      |           |               |
|                        | user_agent      |         |      |           |               |
|                        | proxy_ip        |         |      |           |               |
| email-create           | attachment      | Default |      |           | &#10003;      |
|                        | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| email-delete           | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| email-modify           | attachment      | Default |      |           | &#10003;      |
|                        | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| email-read             | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | dest_user       | Default |      | &#10003;  |               |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| email-recipient-add    | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| email-send             | additional_info | Default |      |           | &#10003;      |
|                        | bytes           | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
| file-delete            | access          | Legacy  |      | &#10003;  |               |
| file-download          | access          |         |      |           | &#10003;      |
| file-permission-modify | access          | Legacy  |      | &#10003;  |               |
| file-read              | access          | Legacy  |      | &#10003;  |               |
| file-upload            | access          |         |      |           | &#10003;      |
| file-write             | access          | Legacy  |      | &#10003;  |               |
| user-delete            | additional_info |         |      |           |               |
|                        | mime            |         |      |           |               |
|                        | dest_host       | Legacy  |      |           | &#10003;      |
|                        | operation       |         |      |           |               |
|                        | url             |         |      |           |               |
|                        | user_agent      |         |      |           |               |
| user-lock              |                 |         |      |           |               |
| user-modify            | dest_host       | Legacy  |      |           | &#10003;      |
|                        | operation       |         |      |           |               |
| user-password-modify   | access          | Default |      |           | &#10003;      |
|                        | mime            | Default |      |           | &#10003;      |
|                        | user_agent      | Default |      |           | &#10003;      |
|                        | url             | Default |      |           | &#10003;      |
| user-password-reset    | access          |         |      |           | &#10003;      |
|                        | mime            |         |      |           | &#10003;      |
|                        | user_agent      |         |      | &#10003;  |               |
|                        | url             |         |      |           | &#10003;      |
| user-unlock            |                 |         |      |           |               |

