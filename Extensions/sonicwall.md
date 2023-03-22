sonicwall
=========

Expression
----------

product = "sonicwall"

Fields
------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_interface  |      |           | &#10003;      |
| protocol       |      |           | &#10003;      |
| bytes_out      |      |           | &#10003;      |
| dest_interface |      |           | &#10003;      |
| bytes_in       |      |           | &#10003;      |
| bytes          |      |           | &#10003;      |

Activity Types
--------------

| Activity Type  | Field             | Status  | Core | Detection | Informational |
| -------------- | ----------------- | ------- | ---- | --------- | ------------- |
| endpoint-login | src_ip            | Default |      | &#10003;  |               |
|                | src_port          | Default |      |           | &#10003;      |
|                | login_type_text   | Default |      |           | &#10003;      |
|                | dest_ip           | Default |      | &#10003;  |               |
|                | realm             | Default |      |           | &#10003;      |
|                | src_host          | Default |      | &#10003;  |               |
|                | session_duration  | Default |      |           | &#10003;      |
|                | dest_port         | Default |      |           | &#10003;      |
|                | user_agent        | Default |      |           | &#10003;      |
| http-session   | src_mac           | Default |      |           | &#10003;      |
|                | category_id       | Default |      |           | &#10003;      |
|                | additional_info   | Default |      |           | &#10003;      |
|                | dest_mac          | Default |      |           | &#10003;      |
|                | firewall          | Default |      |           | &#10003;      |
|                | rule              | Default |      |           | &#10003;      |
|                | message_id        | Default |      |           | &#10003;      |
| vpn-login      | src_port          | Default |      |           | &#10003;      |
|                | src_translated_ip | Default |      |           | &#10003;      |
|                | dest_ip           | Default |      | &#10003;  |               |
|                | dest_host         | Default |      | &#10003;  |               |
|                | realm             | Default |      |           | &#10003;      |
|                | src_host          | Default |      | &#10003;  |               |
|                | dest_port         | Default |      |           | &#10003;      |
|                | user_agent        | Default |      |           | &#10003;      |
|                | session_duration  | Default |      |           | &#10003;      |
| vpn-logout     | src_translated_ip |         |      |           |               |
|                | src_port          |         |      |           |               |
|                | dest_ip           |         |      |           |               |
|                | dest_host         | Legacy  |      |           | &#10003;      |
|                | realm             | Legacy  |      |           | &#10003;      |
|                | src_host          |         |      |           |               |
|                | session_duration  | Legacy  |      | &#10003;  |               |
|                | dest_port         |         |      |           |               |
|                | user_agent        |         |      |           |               |

