unix auditd
===========

Expression
----------

product = "unix auditd"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field                  | Status  | Core | Detection | Informational |
| ----------------------- | ---------------------- | ------- | ---- | --------- | ------------- |
| endpoint-authentication | process_id             | Default |      |           | &#10003;      |
|                         | operation_type         | Default |      |           | &#10003;      |
|                         | service_name           | Default |      |           | &#10003;      |
|                         | process_dir            | Default |      |           | &#10003;      |
|                         | src_host               | Default |      | &#10003;  |               |
|                         | src_port               | Default |      |           | &#10003;      |
|                         | src_ip                 | Default |      | &#10003;  |               |
|                         | account_id             | Default |      |           | &#10003;      |
|                         | event_id               | Default |      |           | &#10003;      |
|                         | user_id                | Default |      |           | &#10003;      |
|                         | process_name           | Default |      |           | &#10003;      |
|                         | dest_ip                | Default |      | &#10003;  |               |
|                         | event_name             | Default |      |           | &#10003;      |
|                         | process_path           | Default |      |           | &#10003;      |
|                         | operation              | Default |      |           | &#10003;      |
|                         | dest_port              | Default |      |           | &#10003;      |
|                         | account                | Default |      | &#10003;  |               |
| endpoint-login          | process_id             | Default |      |           | &#10003;      |
|                         | service_name           | Default |      |           | &#10003;      |
|                         | process_dir            | Default |      |           | &#10003;      |
|                         | src_host               | Default |      | &#10003;  |               |
|                         | result                 | Default |      |           | &#10003;      |
|                         | src_port               | Default |      |           | &#10003;      |
|                         | src_ip                 | Default |      | &#10003;  |               |
|                         | event_id               | Default |      |           | &#10003;      |
|                         | additional_info        | Default |      |           | &#10003;      |
|                         | user_id                | Default |      |           | &#10003;      |
|                         | event_code             | Default |      |           | &#10003;      |
|                         | process_name           | Default |      |           | &#10003;      |
|                         | dest_ip                | Default |      | &#10003;  |               |
|                         | event_name             | Default |      |           | &#10003;      |
|                         | process_path           | Default |      |           | &#10003;      |
|                         | operation              | Default |      |           | &#10003;      |
|                         | dest_port              | Default |      |           | &#10003;      |
|                         | authentication_process | Default |      |           | &#10003;      |
| group-member-add        | user_id                |         |      |           |               |
|                         | session_id             |         |      |           |               |
| group-member-remove     | user_id                |         |      |           |               |
|                         | session_id             |         |      |           |               |
| process-create          | service_name           | Default |      |           | &#10003;      |
|                         | src_port               | Default |      |           | &#10003;      |
|                         | src_ip                 | Default |      | &#10003;  |               |
|                         | account_id             | Default |      |           | &#10003;      |
|                         | event_id               | Default |      |           | &#10003;      |
|                         | user_id                | Default |      |           | &#10003;      |
|                         | additional_info        | Default |      |           | &#10003;      |
|                         | event_code             | Default |      |           | &#10003;      |
|                         | dest_ip                | Default |      | &#10003;  |               |
|                         | event_name             | Default |      |           | &#10003;      |
|                         | dest_host              | Default |      | &#10003;  |               |
|                         | user                   | Default |      | &#10003;  |               |
|                         | dest_port              | Default |      |           | &#10003;      |
| user-create             | process_id             |         |      |           |               |
|                         | user_id                |         |      |           |               |
|                         | session_id             |         |      |           |               |
| user-delete             | user_id                |         |      |           |               |
|                         | session_id             |         |      |           |               |
|                         | dest_user_id           |         |      |           |               |

