password manager pro
====================

Expression
----------

product = "password manager pro"

Fields
------

| Field    | Core     | Detection | Informational |
| -------- | -------- | --------- | ------------- |
| src_ip   |          | &#10003;  |               |
| domain   |          | &#10003;  |               |
| src_host |          | &#10003;  |               |
| user     | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type        | Field      | Status  | Core | Detection | Informational |
| -------------------- | ---------- | ------- | ---- | --------- | ------------- |
| user-password-modify | safe_value | Default |      |           | &#10003;      |
| user-password-read   | dest_ip    |         |      | &#10003;  |               |
|                      | safe_value |         |      |           | &#10003;      |

