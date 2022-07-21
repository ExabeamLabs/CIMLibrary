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

| Activity Type          | Field             | Status  | Core     | Detection | Informational |
| ---------------------- | ----------------- | ------- | -------- | --------- | ------------- |
| app-activity           | src_ip            | Default |          | &#10003;  |               |
|                        | application       | Default |          |           | &#10003;      |
|                        | additional_info   | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | dest_domain       | Default |          |           | &#10003;      |
|                        | event_name        | Default |          |           | &#10003;      |
|                        | dest_user         | Default |          | &#10003;  |               |
|                        | user              | Default | &#10003; | &#10003;  |               |
|                        | object            | Default |          |           | &#10003;      |
| app-login              | result            | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | operation         | Default |          |           | &#10003;      |
|                        | object            | Default |          |           | &#10003;      |
| password-create        | account_domain    | Default |          |           | &#10003;      |
|                        | application       | Default |          |           | &#10003;      |
|                        | additional_info   | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | dest_host         | Default |          | &#10003;  |               |
|                        | operation         | Default |          |           | &#10003;      |
|                        | account           | Default |          | &#10003;  |               |
|                        | object            | Default |          |           | &#10003;      |
| user-permission-modify | src_user          |         |          |           |               |
|                        | session_id        |         |          |           |               |
|                        | src_host          | Legacy  |          |           | &#10003;      |
|                        | src_port          |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | full_name         |         |          |           |               |
|                        | email_user        |         |          |           |               |
|                        | application       |         |          |           |               |
|                        | additional_info   |         |          |           |               |
|                        | dest_ip           |         |          |           |               |
|                        | operating_system  |         |          |           |               |
|                        | dest_host         | Legacy  |          |           | &#10003;      |
|                        | event_name        |         |          |           |               |
|                        | operation         |         |          |           |               |
|                        | dest_port         |         |          |           |               |
| user-switch            | src_ip            |         |          |           |               |
|                        | event_code        |         |          |           |               |
|                        | dest_service_name |         |          |           |               |
|                        | dest_host         |         |          |           |               |
|                        | event_name        |         |          |           |               |
|                        | safe_value        |         |          |           |               |

