microsoft sysmon
================

Expression
----------

product = "microsoft sysmon"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field        | Status | Core | Detection | Informational |
| ------------- | ------------ | ------ | ---- | --------- | ------------- |
| alert-trigger | process_id   |        |      |           |               |
|               | thread_id    |        |      |           |               |
|               | process_guid |        |      |           |               |
|               | process_name | Legacy |      | &#10003;  |               |
|               | user_sid     |        |      |           |               |
|               | dest_host    | Legacy |      | &#10003;  |               |
|               | process_dir  |        |      |           |               |
|               | process_path | Legacy |      | &#10003;  |               |

