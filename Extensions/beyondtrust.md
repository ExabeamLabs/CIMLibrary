beyondtrust
===========

Expression
----------

product = "beyondtrust"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field                 | Status  | Core     | Detection | Informational |
| ---------------------- | --------------------- | ------- | -------- | --------- | ------------- |
| app-activity           | src_ip                | Default |          | &#10003;  |               |
|                        | app                   | Default |          |           | &#10003;      |
|                        | dest_domain_user_name |         |          |           |               |
|                        | additional_info       | Default |          |           | &#10003;      |
|                        | domain                | Default |          |           | &#10003;      |
|                        | dest_domain           | Default |          |           | &#10003;      |
|                        | event_name            | Default |          |           | &#10003;      |
|                        | domain_user_name      |         |          |           |               |
|                        | dest_user             | Default |          | &#10003;  |               |
|                        | user                  | Default | &#10003; | &#10003;  |               |
|                        | object                | Default |          |           | &#10003;      |
| app-login              | result                | Default |          |           | &#10003;      |
|                        | src_ip                | Default |          | &#10003;  |               |
|                        | operation             | Default |          |           | &#10003;      |
|                        | object                | Default |          |           | &#10003;      |
| endpoint-login         | user_info             | Default |          |           | &#10003;      |
| password-create        | app                   | Default |          |           | &#10003;      |
|                        | account_user_name     |         |          |           |               |
|                        | account_domain        | Default |          |           | &#10003;      |
|                        | additional_info       | Default |          |           | &#10003;      |
|                        | domain                | Default |          |           | &#10003;      |
|                        | dest_host             | Default |          | &#10003;  |               |
|                        | operation             | Default |          |           | &#10003;      |
|                        | account               | Default |          | &#10003;  |               |
|                        | object                | Default |          |           | &#10003;      |
| user-permission-modify | app                   |         |          |           |               |
|                        | os                    |         |          |           |               |
|                        | src_user              |         |          |           |               |
|                        | session_id            |         |          |           |               |
|                        | src_host              | Legacy  |          |           | &#10003;      |
|                        | src_port              |         |          |           |               |
|                        | src_ip                |         |          |           |               |
|                        | full_name             |         |          |           |               |
|                        | email_user            |         |          |           |               |
|                        | additional_info       |         |          |           |               |
|                        | dest_ip               |         |          |           |               |
|                        | dest_host             | Legacy  |          |           | &#10003;      |
|                        | event_name            |         |          |           |               |
|                        | operation             |         |          |           |               |
|                        | dest_port             |         |          |           |               |
| user-switch            | src_ip                |         |          |           |               |
|                        | event_code            |         |          |           |               |
|                        | dest_service_name     |         |          |           |               |
|                        | dest_host             |         |          |           |               |
|                        | event_name            |         |          |           |               |
|                        | safe_value            |         |          |           |               |

