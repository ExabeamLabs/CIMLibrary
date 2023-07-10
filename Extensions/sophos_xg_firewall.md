sophos xg firewall
==================

Expression
----------

product = "sophos xg firewall"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field             | Status  | Core | Detection | Informational |
| --------------- | ----------------- | ------- | ---- | --------- | ------------- |
| http-session    | file_name         | Default |      |           | &#10003;      |
| network-session | src_interface     | Default |      |           | &#10003;      |
|                 | device_id         | Default |      |           | &#10003;      |
|                 | dest_interface    | Default |      |           | &#10003;      |
|                 | src_country_code  | Default |      |           | &#10003;      |
|                 | operation         | Default |      |           | &#10003;      |
|                 | dest_country_code | Default |      |           | &#10003;      |
| vpn-login       | src_port          | Default |      |           | &#10003;      |
|                 | src_interface     | Default |      |           | &#10003;      |
|                 | protocol          | Default |      |           | &#10003;      |
|                 | dest_interface    | Default |      |           | &#10003;      |
|                 | dest_ip           | Default |      | &#10003;  |               |
|                 | operation         | Default |      |           | &#10003;      |
|                 | dest_port         | Default |      |           | &#10003;      |

