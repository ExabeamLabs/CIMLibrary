axway sftp
==========

Expression
----------

product = "axway sftp"

Fields
------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| src_ip     |          | &#10003;  |               |
| user_dn    |          |           | &#10003;      |
| dest_ip    |          | &#10003;  |               |
| domain     |          |           | &#10003;      |
| event_name |          |           | &#10003;      |
| user       | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type      | Field                  | Status  | Core | Detection | Informational |
| ------------------ | ---------------------- | ------- | ---- | --------- | ------------- |
| app-authentication | src_ip                 | Default |      | &#10003;  |               |
|                    | src_port               | Default |      |           | &#10003;      |
|                    | auth_method            | Default |      |           | &#10003;      |
| endpoint-login     | authentication_package | Default |      |           | &#10003;      |
| file-upload        |                        |         |      |           |               |

