anyconnect
==========

Expression
----------

product = "any connect"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field                | Status  | Core | Detection | Informational |
| --------------- | -------------------- | ------- | ---- | --------- | ------------- |
| network-session | system_manufacturer  | Default |      |           | &#10003;      |
|                 | os                   | Default |      |           | &#10003;      |
|                 | bytes_in             | Default |      |           | &#10003;      |
|                 | module_hash_names    | Default |      |           | &#10003;      |
|                 | parent_process_name  | Default |      |           | &#10003;      |
|                 | parent_process_hash  | Default |      |           | &#10003;      |
|                 | os_version           | Default |      |           | &#10003;      |
|                 | os_environment       | Default |      |           | &#10003;      |
|                 | bytes_out            | Default |      |           | &#10003;      |
|                 | process_hash         | Default |      |           | &#10003;      |
|                 | virtual_station_name | Default |      |           | &#10003;      |
|                 | system_type          | Default |      |           | &#10003;      |
|                 | process_name         | Default |      |           | &#10003;      |
|                 | domain               | Default |      |           | &#10003;      |
|                 | packet_rate          | Default |      |           | &#10003;      |
|                 | udid                 | Default |      |           | &#10003;      |
|                 | user                 | Default |      | &#10003;  |               |
| vpn-login       | src_translated_ip    | Default |      |           | &#10003;      |
|                 | os                   | Default |      |           | &#10003;      |
|                 | event_code           | Default |      |           | &#10003;      |
|                 | dest_ip              | Default |      | &#10003;  |               |
|                 | realm                | Default |      |           | &#10003;      |
|                 | priority             | Default |      |           | &#10003;      |
| vpn-logout      | dest_ip              |         |      | &#10003;  |               |
|                 | realm                | Legacy  |      |           | &#10003;      |
|                 | src_host             |         |      | &#10003;  |               |
|                 | session_duration     | Legacy  |      | &#10003;  |               |
|                 | dest_port            |         |      | &#10003;  |               |

