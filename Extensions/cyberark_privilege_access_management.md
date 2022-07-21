cyberark privilege access management
====================================

Expression
----------

product = "cyberark vault"

Fields
------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| src_ip            |      |           | &#10003;      |
| event_code        |      |           | &#10003;      |
| dest_ip           |      |           | &#10003;      |
| dest_service_name |      |           | &#10003;      |
| dest_host         |      |           | &#10003;      |
| safe_value        |      |           | &#10003;      |
| dest_port         |      |           | &#10003;      |

Activity Types
--------------

| Activity Type          | Field           | Status  | Core     | Detection | Informational |
| ---------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity           | file_path       | Default |          |           | &#10003;      |
|                        | file_ext        | Default |          |           | &#10003;      |
|                        | resource        | Default |          |           | &#10003;      |
|                        | file_name       | Default |          |           | &#10003;      |
|                        | file_type       | Default |          |           | &#10003;      |
|                        | process_name    | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | file_dir        | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
|                        | user            | Default |          | &#10003;  |               |
|                        | object          | Default |          |           | &#10003;      |
| app-login              | event_subtype   | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
| app-logout             | domain          | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| app-notification       | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| endpoint-login         | process_name    | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
|                        | command         | Default |          |           | &#10003;      |
| file-delete            | db_name         |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | domain          |         |          |           |               |
|                        | device_type     |         |          |           |               |
|                        | src_host        | Legacy  |          | &#10003;  |               |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | record_type     |         |          |           |               |
|                        | safe_name       |         |          |           |               |
| file-permission-modify | db_name         |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | domain          |         |          |           |               |
|                        | device_type     |         |          |           |               |
|                        | src_host        |         |          |           |               |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | record_type     |         |          |           |               |
|                        | safe_name       |         |          |           |               |
| file-property-delete   | domain          | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
| file-read              | db_name         |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | domain          |         |          |           |               |
|                        | device_type     | Legacy  |          |           | &#10003;      |
|                        | src_host        | Legacy  |          | &#10003;  |               |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | record_type     |         |          |           |               |
|                        | safe_name       |         |          |           |               |
| file-write             | db_name         |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | domain          |         |          |           |               |
|                        | device_type     | Legacy  |          |           | &#10003;      |
|                        | src_host        |         |          |           |               |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | record_type     |         |          |           |               |
|                        | safe_name       |         |          |           |               |
| password-create        | protocol        | Default |          |           | &#10003;      |
|                        | process_name    | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | session_id      | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
|                        | command         | Default |          |           | &#10003;      |
| password-use           | protocol        | Default |          |           | &#10003;      |
|                        | process_name    | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | session_id      | Default |          |           | &#10003;      |
|                        | src_host        | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
|                        | command         | Default |          |           | &#10003;      |
| user-password-modify   | src_host        | Default |          | &#10003;  |               |
| user-password-read     | gateway_station |         |          |           |               |
|                        | process_name    | Legacy  |          |           | &#10003;      |
|                        | session_id      |         |          |           |               |
|                        | src_host        | Legacy  |          |           | &#10003;      |
|                        | command         |         |          |           |               |
| user-password-reset    | src_host        |         |          |           |               |

