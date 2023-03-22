citrix gateway
==============

Expression
----------

product = "citrix gateway"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type      | Field                | Status  | Core | Detection | Informational |
| ------------------ | -------------------- | ------- | ---- | --------- | ------------- |
| http-session       | protocol             | Default |      |           | &#10003;      |
|                    | dest_host            | Default |      | &#10003;  |               |
|                    | result_code          | Default |      |           | &#10003;      |
| network-session    | src_translated_ip    | Default |      |           | &#10003;      |
|                    | result               | Default |      |           | &#10003;      |
|                    | bytes_out            | Default |      |           | &#10003;      |
|                    | bytes_in             | Default |      |           | &#10003;      |
|                    | event_name           | Default |      |           | &#10003;      |
|                    | dest_translated_port | Default |      |           | &#10003;      |
|                    | src_translated_port  | Default |      |           | &#10003;      |
|                    | operation            | Default |      |           | &#10003;      |
|                    | dest_translated_ip   | Default |      |           | &#10003;      |
| process-create     | dest_ip              | Default |      | &#10003;  |               |
|                    | process_command_line | Default |      |           | &#10003;      |
|                    | user                 | Default |      | &#10003;  |               |
| vpn-authentication | method               | Default |      |           | &#10003;      |
|                    | dest_ip              | Default |      | &#10003;  |               |
|                    | action               | Default |      |           | &#10003;      |
|                    | event_name           | Default |      |           | &#10003;      |
|                    | session_id           | Default |      |           | &#10003;      |
|                    | dest_host            | Default |      | &#10003;  |               |
|                    | src_host             | Default |      | &#10003;  |               |
|                    | event_category       | Default |      |           | &#10003;      |
|                    | uri                  | Default |      |           | &#10003;      |
|                    | dest_port            | Default |      |           | &#10003;      |
|                    | object               | Default |      |           | &#10003;      |
| vpn-login          | src_translated_ip    | Default |      |           | &#10003;      |
|                    | dest_ip              | Default |      | &#10003;  |               |
|                    | dest_host            | Default |      | &#10003;  |               |
|                    | session_id           | Default |      |           | &#10003;      |
|                    | vpn_client_type      | Default |      |           | &#10003;      |
|                    | realm                | Default |      |           | &#10003;      |
|                    | src_host             | Default |      | &#10003;  |               |
|                    | user_agent           | Default |      |           | &#10003;      |
| vpn-logout         | bytes_in             |         |      | &#10003;  |               |
|                    | session_id           |         |      |           | &#10003;      |
|                    | vpn_client_type      |         |      | &#10003;  |               |
|                    | src_host             |         |      | &#10003;  |               |
|                    | source_connection_id |         |      |           | &#10003;      |
|                    | src_port             |         |      | &#10003;  |               |
|                    | duration             |         |      | &#10003;  |               |
|                    | src_translated_ip    |         |      | &#10003;  |               |
|                    | bytes_out            | Legacy  |      | &#10003;  |               |
|                    | dest_ip              |         |      | &#10003;  |               |
|                    | event_name           |         |      | &#10003;  |               |
|                    | dest_host            | Legacy  |      |           | &#10003;      |
|                    | dest_port            |         |      | &#10003;  |               |
| vpn-session        | src_port             |         |      | &#10003;  |               |
|                    | duration             |         |      | &#10003;  |               |
|                    | src_translated_ip    |         |      | &#10003;  |               |
|                    | bytes_out            |         |      | &#10003;  |               |
|                    | bytes_in             |         |      | &#10003;  |               |
|                    | event_name           |         |      | &#10003;  |               |
|                    | action               |         |      | &#10003;  |               |
|                    | session_id           |         |      |           | &#10003;      |
|                    | access_group         |         |      | &#10003;  |               |
|                    | dest_port            |         |      | &#10003;  |               |
|                    | dest_translated_ip   |         |      | &#10003;  |               |

