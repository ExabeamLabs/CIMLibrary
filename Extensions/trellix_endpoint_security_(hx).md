trellix endpoint security (hx)
==============================

Expression
----------

product = "trellix endpoint security (hx)"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field                | Status | Core     | Detection | Informational |
| ------------- | -------------------- | ------ | -------- | --------- | ------------- |
| alert-trigger | process_name         | Legacy |          | &#10003;  |               |
|               | alert_id             | Legacy |          |           | &#10003;      |
|               | dest_ip              | Legacy | &#10003; | &#10003;  |               |
|               | domain               |        |          |           |               |
|               | hash_md5             |        |          |           |               |
|               | event_name           |        |          |           |               |
|               | domain_user_name     |        |          |           |               |
|               | process_command_line |        |          |           |               |
|               | user                 | Legacy |          | &#10003;  |               |
| file-write    | event_code           |        |          |           | &#10003;      |
|               | process_name         | Legacy |          |           | &#10003;      |
|               | dest_ip              |        | &#10003; | &#10003;  |               |
|               | domain               |        |          |           | &#10003;      |
|               | event_name           |        |          |           | &#10003;      |
|               | domain_user_name     |        |          |           |               |
|               | operation            |        |          |           | &#10003;      |
|               | user                 | Legacy | &#10003; | &#10003;  |               |
| http-session  |                      |        |          |           |               |

