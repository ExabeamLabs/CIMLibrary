globalprotect
=============

Expression
----------

product = "palo alto global protect"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| src_ip           |          | &#10003;  |               |
| src_country      |          |           | &#10003;      |
| domain           |          | &#10003;  |               |
| operating_system |          |           | &#10003;      |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type        | Field           | Status  | Core | Detection | Informational |
| -------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity         | src_mac         | Default |      |           | &#10003;      |
|                      | auth_method     | Default |      |           | &#10003;      |
|                      | application     | Default |      |           | &#10003;      |
|                      | additional_info | Default |      |           | &#10003;      |
|                      | dest_ip         | Default |      | &#10003;  |               |
|                      | vpn_client      | Default |      |           | &#10003;      |
|                      | event_name      | Default |      |           | &#10003;      |
|                      | device_type     | Default |      |           | &#10003;      |
|                      | src_host        | Default |      | &#10003;  |               |
|                      | object          | Default |      |           | &#10003;      |
| app-login            |                 |         |      |           |               |
| configuration-modify | object          |         |      |           | &#10003;      |
| vpn-authentication   |                 |         |      |           |               |
| vpn-login            | vpn_client      | Default |      |           | &#10003;      |
| vpn-logout           | vpn_client      |         |      |           | &#10003;      |

