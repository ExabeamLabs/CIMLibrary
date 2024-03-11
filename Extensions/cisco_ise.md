cisco ise
=========

Expression
----------

product = "cisco ise"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      |           | &#10003;      |

Activity Types
--------------

| Activity Type           | Field              | Status  | Core | Detection | Informational |
| ----------------------- | ------------------ | ------- | ---- | --------- | ------------- |
| app-activity            | src_ip             | Default |      | &#10003;  |               |
|                         | app                | Default |      |           | &#10003;      |
|                         | privileges         | Default |      |           | &#10003;      |
|                         | dest_ip            | Default |      | &#10003;  |               |
|                         | user               | Default |      | &#10003;  |               |
| configuration-modify    | severity           |         |      |           |               |
|                         | additional_info    |         |      |           |               |
|                         | event_code         |         |      |           |               |
|                         | domain             |         |      |           |               |
|                         | event_name         |         |      |           |               |
|                         | user               |         |      |           |               |
|                         | operation          |         |      |           |               |
|                         | admin_interface    |         |      |           |               |
|                         | object             |         |      |           |               |
| endpoint-authentication | severity           | Default |      |           | &#10003;      |
|                         | computer_name      | Default |      |           | &#10003;      |
|                         | src_mac            | Default |      |           | &#10003;      |
|                         | radius_flow_type   | Default |      |           | &#10003;      |
|                         | access_type        | Default |      |           | &#10003;      |
|                         | user_dn            | Default |      |           | &#10003;      |
|                         | dest_mac           | Default |      |           | &#10003;      |
|                         | session_id         | Default |      |           | &#10003;      |
|                         | src_host           | Default |      | &#10003;  |               |
|                         | ssid               | Default |      |           | &#10003;      |
|                         | nas_ip_address     | Default |      |           | &#10003;      |
|                         | network            | Default |      |           | &#10003;      |
|                         | identity_group     | Default |      |           | &#10003;      |
|                         | protocol           | Default |      |           | &#10003;      |
|                         | user_type          | Default |      |           | &#10003;      |
|                         | dest_ip            | Default |      | &#10003;  |               |
|                         | location           | Default |      |           | &#10003;      |
|                         | acs_session_id     | Default |      |           | &#10003;      |
|                         | auth_server        | Default |      |           | &#10003;      |
|                         | dest_port          | Default |      |           | &#10003;      |
|                         | calling_station_id | Default |      |           | &#10003;      |
| endpoint-login          | severity           | Default |      |           | &#10003;      |
|                         | additional_info    | Default |      |           | &#10003;      |
|                         | event_code         | Default |      |           | &#10003;      |
|                         | event_name         | Default |      |           | &#10003;      |
|                         | category           | Default |      |           | &#10003;      |
|                         | admin_interface    | Default |      |           | &#10003;      |
| vpn-login               | src_translated_ip  | Default |      |           | &#10003;      |
|                         | os                 | Default |      |           | &#10003;      |
|                         | event_code         | Default |      |           | &#10003;      |
|                         | dest_ip            | Default |      | &#10003;  |               |
|                         | os_version         | Default |      |           | &#10003;      |
|                         | badge_id           | Default |      |           | &#10003;      |
|                         | dest_host          | Default |      | &#10003;  |               |
|                         | session_id         | Default |      |           | &#10003;      |
|                         | event_name         | Default |      |           | &#10003;      |
|                         | realm              | Default |      |           | &#10003;      |
| vpn-logout              | src_translated_ip  |         |      |           |               |
|                         | bytes_out          | Legacy  |      | &#10003;  |               |
|                         | bytes_in           |         |      |           |               |
|                         | additional_info    |         |      |           |               |
|                         | dest_ip            |         |      |           |               |
|                         | dest_host          | Legacy  |      |           | &#10003;      |
|                         | session_duration   | Legacy  |      | &#10003;  |               |

