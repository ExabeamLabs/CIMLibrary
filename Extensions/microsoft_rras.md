microsoft rras
==============

Expression
----------

product = "microsoft rras"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| session_id |      |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field       | Status | Core | Detection | Informational |
| ------------------ | ----------- | ------ | ---- | --------- | ------------- |
| vpn-authentication |             |        |      |           |               |
| vpn-login          |             |        |      |           |               |
| vpn-logout         | bytes_out   | Legacy |      | &#10003;  |               |
|                    | bytes_in    |        |      |           |               |
|                    | session_sec |        |      |           |               |
|                    | session_min |        |      |           |               |

