fortinet vpn
============

Expression
----------

product = "fortinet vpn"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field             | Status  | Core | Detection | Informational |
| ------------------ | ----------------- | ------- | ---- | --------- | ------------- |
| vpn-authentication | additional_info   | Default |      |           | &#10003;      |
| vpn-login          | src_translated_ip | Default |      |           | &#10003;      |
|                    | realm             | Default |      |           | &#10003;      |
| vpn-logout         | src_translated_ip |         |      |           | &#10003;      |
|                    | bytes_out         | Legacy  |      | &#10003;  |               |
|                    | bytes_in          |         |      |           | &#10003;      |
|                    | realm             | Legacy  |      |           | &#10003;      |

