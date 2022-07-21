exabeam dl
==========

Expression
----------

product = "exabeam dl"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field           | Status  | Core     | Detection | Informational |
| ---------------------- | --------------- | ------- | -------- | --------- | ------------- |
| alert-trigger          | event_id        |         |          |           | &#10003;      |
|                        | dest_host       | Legacy  |          | &#10003;  |               |
|                        | original_score  |         |          |           |               |
|                        | src_host        | Legacy  | &#10003; | &#10003;  |               |
|                        | mitre_labels    |         |          |           | &#10003;      |
|                        | alert_reason    |         |          |           | &#10003;      |
|                        | usecases        |         |          |           | &#10003;      |
|                        | user            | Legacy  |          | &#10003;  |               |
|                        | event_time      |         |          |           | &#10003;      |
|                        | log_time        |         |          |           |               |
|                        | labels          |         |          |           | &#10003;      |
| app-activity           | src_ip          | Default |          | &#10003;  |               |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
| app-login              | src_ip          | Default |          | &#10003;  |               |
|                        | additional_info | Default |          |           | &#10003;      |
| app-notification       | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| group-modify           | src_ip          |         |          |           |               |
|                        | application     |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; |           |               |
|                        | operation       |         |          |           |               |
| log_source-add         | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| log_source-modify      | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| role-delete            | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| role-permission-modify | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| rule-create            | src_ip          | Default |          | &#10003;  |               |
|                        | application     | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| rule-trigger           | rule_severity   | Default |          |           | &#10003;      |
|                        | rule            | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
|                        | usecases        | Default |          |           | &#10003;      |
|                        | log_time        | Default |          |           | &#10003;      |
|                        | labels          | Default |          |           | &#10003;      |
|                        | src_ip          | Default |          | &#10003;  |               |
|                        | trigger_time    | Default |          |           | &#10003;      |
|                        | event_id        | Default |          |           | &#10003;      |
|                        | rule_reason     | Default |          |           | &#10003;      |
|                        | dest_ip         | Default |          | &#10003;  |               |
|                        | dest_host       | Default |          | &#10003;  |               |
|                        | mitre_labels    | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | event_time      | Default |          |           | &#10003;      |

