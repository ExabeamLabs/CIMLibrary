airlock web application firewall
================================

Expression
----------

product = "airlock waf"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| action |      |           | &#10003;      |

Activity Types
--------------

| Activity Type   | Field           | Status  | Core     | Detection | Informational |
| --------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-login       | file_path       | Default |          |           | &#10003;      |
|                 | file_name       | Default |          |           | &#10003;      |
|                 | alert_severity  | Default |          |           | &#10003;      |
|                 | file_dir        | Default |          |           | &#10003;      |
|                 | session_id      | Default |          |           | &#10003;      |
|                 | src_port        | Default |          |           | &#10003;      |
|                 | src_ip          | Default |          | &#10003;  |               |
|                 | file_ext        | Default |          |           | &#10003;      |
|                 | event_code      | Default |          |           | &#10003;      |
|                 | bytes           | Default |          |           | &#10003;      |
|                 | dest_ip         | Default |          | &#10003;  |               |
|                 | event_name      | Default |          |           | &#10003;      |
|                 | dest_port       | Default |          |           | &#10003;      |
| file-delete     | src_port        |         |          |           |               |
|                 | src_ip          |         |          |           |               |
|                 | event_code      |         |          |           |               |
|                 | bytes           |         |          |           |               |
|                 | alert_severity  |         |          |           |               |
|                 | dest_ip         |         |          |           |               |
|                 | domain          |         |          |           |               |
|                 | session_id      |         |          |           |               |
|                 | event_name      |         |          |           |               |
|                 | user            | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_port       |         |          |           |               |
| file-download   | src_port        |         |          |           |               |
|                 | src_ip          |         |          |           |               |
|                 | event_code      |         |          |           |               |
|                 | bytes           | Legacy  |          | &#10003;  |               |
|                 | alert_severity  |         |          |           |               |
|                 | dest_ip         |         |          |           |               |
|                 | domain          |         |          |           |               |
|                 | session_id      |         |          |           |               |
|                 | event_name      |         |          |           |               |
|                 | user            | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_port       |         |          |           |               |
| file-upload     | src_port        |         |          |           |               |
|                 | src_ip          |         |          |           |               |
|                 | event_code      |         |          |           |               |
|                 | bytes           |         |          |           |               |
|                 | alert_severity  |         |          |           |               |
|                 | dest_ip         |         |          |           |               |
|                 | domain          |         |          |           |               |
|                 | session_id      |         |          |           |               |
|                 | event_name      |         |          |           |               |
|                 | user            | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_port       |         |          |           |               |
| file-write      | src_port        |         |          |           |               |
|                 | src_ip          |         |          |           |               |
|                 | event_code      |         |          |           |               |
|                 | bytes           | Legacy  |          | &#10003;  |               |
|                 | alert_severity  |         |          |           |               |
|                 | dest_ip         |         |          |           |               |
|                 | domain          |         |          |           |               |
|                 | session_id      |         |          |           |               |
|                 | event_name      |         |          |           |               |
|                 | user            | Legacy  | &#10003; | &#10003;  |               |
|                 | dest_port       |         |          |           |               |
| http-session    | additional_info | Default |          |           | &#10003;      |
|                 | result_code     | Default |          |           | &#10003;      |
| network-session | file_path       | Default |          |           | &#10003;      |
|                 | file_ext        | Default |          |           | &#10003;      |
|                 | event_code      | Default |          |           | &#10003;      |
|                 | file_name       | Default |          |           | &#10003;      |
|                 | alert_severity  | Default |          |           | &#10003;      |
|                 | domain          | Default |          |           | &#10003;      |
|                 | file_dir        | Default |          |           | &#10003;      |
|                 | session_id      | Default |          |           | &#10003;      |
|                 | event_name      | Default |          |           | &#10003;      |
|                 | operation       | Default |          |           | &#10003;      |
|                 | user            | Default |          | &#10003;  |               |
| vpn-logout      | src_port        |         |          |           |               |
|                 | file_path       |         |          |           |               |
|                 | file_ext        |         |          |           |               |
|                 | event_code      |         |          |           |               |
|                 | bytes           |         |          |           |               |
|                 | file_name       |         |          |           |               |
|                 | alert_severity  |         |          |           |               |
|                 | dest_ip         |         |          |           |               |
|                 | file_dir        |         |          |           |               |
|                 | session_id      |         |          |           |               |
|                 | event_name      |         |          |           |               |
|                 | dest_port       |         |          |           |               |

