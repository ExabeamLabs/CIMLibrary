auditbeat
=========

Expression
----------

product = "auditbeat"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field                | Status  | Core     | Detection | Informational |
| ----------------------- | -------------------- | ------- | -------- | --------- | ------------- |
| app-activity            | parent_process_id    | Default |          |           | &#10003;      |
|                         | process_id           | Default |          |           | &#10003;      |
|                         | syscall              | Default |          |           | &#10003;      |
|                         | operation_type       | Default |          |           | &#10003;      |
|                         | os                   | Default |          |           | &#10003;      |
|                         | process_command_line | Default |          |           | &#10003;      |
|                         | group_id             | Default |          |           | &#10003;      |
|                         | process_name         | Default |          |           | &#10003;      |
|                         | domain               | Default |          |           | &#10003;      |
|                         | process_path         | Default |          |           | &#10003;      |
|                         | tag                  | Default |          |           | &#10003;      |
|                         | user                 | Default | &#10003; | &#10003;  |               |
|                         | account              | Default |          | &#10003;  |               |
| endpoint-authentication | src_ip               | Default |          | &#10003;  |               |
|                         | additional_info      | Default |          |           | &#10003;      |
|                         | event_name           | Default |          |           | &#10003;      |
| network-session         | process_id           | Default |          |           | &#10003;      |
|                         | process_name         | Default |          |           | &#10003;      |
|                         | domain               | Default |          |           | &#10003;      |
|                         | process_dir          | Default |          |           | &#10003;      |
|                         | process_path         | Default |          |           | &#10003;      |
|                         | user                 | Default |          | &#10003;  |               |
|                         | direction            | Default |          |           | &#10003;      |
| process-create          | user_id              | Default |          |           | &#10003;      |
|                         | additional_info      | Default |          |           | &#10003;      |
|                         | domain               | Default |          |           | &#10003;      |
|                         | hash_md5             | Default |          |           | &#10003;      |
|                         | user                 | Default |          | &#10003;  |               |
| process-modify          | result               | Default |          |           | &#10003;      |
|                         | app                  | Default |          |           | &#10003;      |
|                         | audit_id             | Default |          |           | &#10003;      |
|                         | os                   | Default |          |           | &#10003;      |
|                         | operation_type       | Default |          |           | &#10003;      |
|                         | group_id             | Default |          |           | &#10003;      |
|                         | event_category       | Default |          |           | &#10003;      |
|                         | user                 | Default |          | &#10003;  |               |
|                         | operation            | Default |          |           | &#10003;      |
|                         | tags                 | Default |          |           | &#10003;      |

