cisco adaptive security appliance
=================================

Expression
----------

product = "cisco asa"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| event_code |      | &#10003;  |               |

Activity Types
--------------

| Activity Type           | Field                 | Status  | Core     | Detection | Informational |
| ----------------------- | --------------------- | ------- | -------- | --------- | ------------- |
| app-authentication      | result                | Default |          |           | &#10003;      |
|                         | src_mac               | Default |          |           | &#10003;      |
|                         | src_interface         | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
| app-login               | src_ip                | Default |          | &#10003;  |               |
|                         | auth                  | Default |          |           | &#10003;      |
|                         | additional_info       | Default |          |           | &#10003;      |
|                         | dest_ip               | Default | &#10003; | &#10003;  |               |
|                         | dest_host             | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
| database-login          | src_ip                | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
| dns-response            | event_name            |         |          | &#10003;  |               |
|                         | priority              |         |          | &#10003;  |               |
| endpoint-authentication | src_ip                | Default |          | &#10003;  |               |
|                         | dest_ip               | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
| file-download           | priority              |         |          | &#10003;  |               |
|                         | src_ip                |         |          | &#10003;  |               |
|                         | src_port              |         |          | &#10003;  |               |
|                         | protocol              |         |          | &#10003;  |               |
|                         | web_domain            |         |          | &#10003;  |               |
|                         | bytes                 | Legacy  |          | &#10003;  |               |
|                         | dest_ip               |         | &#10003; | &#10003;  |               |
|                         | action                |         |          | &#10003;  |               |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
|                         | dest_port             |         |          | &#10003;  |               |
|                         | user_agent            |         |          | &#10003;  |               |
|                         | policy                |         |          | &#10003;  |               |
|                         | direction             |         |          | &#10003;  |               |
| http-session            | domain                | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
| network-traffic         | src_interface         | Default |          |           | &#10003;      |
|                         | dest_interface        | Default |          |           | &#10003;      |
|                         | dest_translated_host  | Default |          |           | &#10003;      |
|                         | src_translated_host   | Default |          |           | &#10003;      |
|                         | domain_user_name      |         |          |           |               |
|                         | src_host              | Default |          | &#10003;  |               |
|                         | dest_translated_ip    | Default |          |           | &#10003;      |
|                         | src_translated_ip     | Default |          |           | &#10003;      |
|                         | duration              | Default |          |           | &#10003;      |
|                         | connection_id         | Default |          |           | &#10003;      |
|                         | domain                | Default |          |           | &#10003;      |
|                         | dest_host             | Default |          | &#10003;  |               |
|                         | dest_translated_port  | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | src_translated_port   | Default |          |           | &#10003;      |
|                         | user                  | Default |          | &#10003;  |               |
|                         | operation             | Default |          |           | &#10003;      |
|                         | direction             | Default |          |           | &#10003;      |
| process-create          | src_ip                | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | process_command_line  | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
|                         | user                  | Default | &#10003; | &#10003;  |               |
| vpn-authentication      | dest_ip               | Default |          | &#10003;  |               |
|                         | dest_host             | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
| vpn-login               | src_mac               | Default |          |           | &#10003;      |
|                         | src_interface         | Default |          |           | &#10003;      |
|                         | client_system         | Default |          |           | &#10003;      |
|                         | client_system_version | Default |          |           | &#10003;      |
|                         | group_name            | Default |          |           | &#10003;      |
|                         | src_host              | Default |          | &#10003;  |               |
|                         | priority              | Default |          |           | &#10003;      |
|                         | result                | Default |          |           | &#10003;      |
|                         | src_translated_ip     | Default |          |           | &#10003;      |
|                         | dest_ip               | Default |          | &#10003;  |               |
|                         | dest_host             | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | realm                 | Default |          |           | &#10003;      |
| vpn-logout              | src_translated_ip     |         |          | &#10003;  |               |
|                         | bytes_out             | Legacy  |          | &#10003;  |               |
|                         | group_name            |         |          | &#10003;  |               |
|                         | bytes_in              |         |          | &#10003;  |               |
|                         | session_sec           |         |          |           | &#10003;      |
|                         | dest_ip               |         |          | &#10003;  |               |
|                         | session_min           |         |          |           | &#10003;      |
|                         | dest_host             | Legacy  |          |           | &#10003;      |
|                         | realm                 | Legacy  |          |           | &#10003;      |
|                         | priority              |         |          | &#10003;  |               |
|                         | session_hour          |         |          |           | &#10003;      |
|                         | session_day           |         |          |           | &#10003;      |

