epic siem
=========

Expression
----------

product = "epic siem"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type        | Field           | Status  | Core | Detection | Informational |
| -------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity         | app             | Default |      |           | &#10003;      |
|                      | resource        | Default |      |           | &#10003;      |
|                      | local_user_name |         |      |           |               |
|                      | src_host        | Default |      | &#10003;  |               |
|                      | result          | Default |      |           | &#10003;      |
|                      | src_ip          | Default |      | &#10003;  |               |
|                      | event_id        | Default |      |           | &#10003;      |
|                      | additional_info | Default |      |           | &#10003;      |
|                      | user_id         | Default |      |           | &#10003;      |
|                      | dest_ip         | Default |      | &#10003;  |               |
|                      | dest_host       | Default |      | &#10003;  |               |
|                      | user            | Default |      | &#10003;  |               |
|                      | account         | Default |      | &#10003;  |               |
|                      | object          | Default |      |           | &#10003;      |
| app-authentication   | dest_host       | Default |      | &#10003;  |               |
|                      | src_host        | Default |      | &#10003;  |               |
| app-login            | resource        | Default |      |           | &#10003;      |
|                      | additional_info | Default |      |           | &#10003;      |
|                      | dest_ip         | Default |      | &#10003;  |               |
|                      | dest_host       | Default |      | &#10003;  |               |
|                      | src_host        | Default |      | &#10003;  |               |
|                      | operation       | Default |      |           | &#10003;      |
| user-password-modify | src_ip          | Default |      | &#10003;  |               |
|                      | event_id        | Default |      |           | &#10003;      |
|                      | resource        | Default |      |           | &#10003;      |
|                      | additional_info | Default |      |           | &#10003;      |
|                      | user_id         | Default |      |           | &#10003;      |
|                      | dest_ip         | Default |      | &#10003;  |               |
|                      | src_host        | Default |      | &#10003;  |               |
|                      | operation       | Default |      |           | &#10003;      |
|                      | object          | Default |      |           | &#10003;      |
| user-switch          | result          |         |      |           |               |
|                      | additional_info |         |      |           |               |
|                      | dest_host       |         |      |           |               |
|                      | src_host        |         |      |           |               |
|                      | operation       |         |      |           |               |

