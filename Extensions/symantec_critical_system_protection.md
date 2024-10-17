symantec critical system protection
===================================

Expression
----------

product = "symantec critical system protection"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ip             |      | &#10003;  |               |
| result             |      |           | &#10003;      |
| login_type         |      |           | &#10003;      |
| event_code         |      |           | &#10003;      |
| domain             |      | &#10003;  |               |
| dest_ip            |      | &#10003;  |               |
| rule               |      |           | &#10003;      |
| policy_name        |      |           | &#10003;      |
| session_id         |      |           | &#10003;      |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| user               |      | &#10003;  |               |

Activity Types
--------------

| Activity Type  | Field               | Status  | Core | Detection | Informational |
| -------------- | ------------------- | ------- | ---- | --------- | ------------- |
| endpoint-login | process_name        | Default |      |           | &#10003;      |
|                | event_name          | Default |      |           | &#10003;      |
|                | process_path        | Default |      |           | &#10003;      |
|                | parent_process_path | Default |      |           | &#10003;      |
| group-create   |                     |         |      |           |               |
| group-delete   |                     |         |      |           |               |
| group-modify   | old_attribute       |         |      |           | &#10003;      |
|                | new_attribute       |         |      |           | &#10003;      |
| user-create    | group_name          |         |      |           | &#10003;      |
| user-delete    |                     |         |      |           |               |
| user-modify    | old_attribute       |         |      |           | &#10003;      |
|                | new_attribute       |         |      |           | &#10003;      |
| user-switch    | process_name        |         |      | &#10003;  |               |

