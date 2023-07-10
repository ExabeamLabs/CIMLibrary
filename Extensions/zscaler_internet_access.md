zscaler internet access
=======================

Expression
----------

product = "zscaler internet access"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| result           |          |           | &#10003;      |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field            | Status  | Core     | Detection | Informational |
| --------------- | ---------------- | ------- | -------- | --------- | ------------- |
| alert-trigger   | app              |         |          |           |               |
|                 | file_name        | Legacy  | &#10003; |           |               |
|                 | domain_user_name |         |          |           |               |
|                 | target           |         |          |           |               |
|                 | result           |         |          |           |               |
|                 | src_ip           | Legacy  | &#10003; | &#10003;  |               |
|                 | dlp_dict         |         |          |           |               |
|                 | protocol         | Legacy  |          | &#10003;  |               |
|                 | additional_info  |         |          |           |               |
|                 | browser          |         |          |           |               |
|                 | dest_ip          | Legacy  | &#10003; | &#10003;  |               |
|                 | domain           |         |          |           |               |
|                 | hash_md5         |         |          |           |               |
|                 | department       |         |          |           |               |
|                 | user             | Legacy  |          | &#10003;  |               |
|                 | user_agent       |         |          |           |               |
|                 | policy           |         |          |           |               |
| app-login       | src_ip           | Default |          | &#10003;  |               |
|                 | bytes_out        | Default |          |           | &#10003;      |
|                 | bytes_in         | Default |          |           | &#10003;      |
|                 | client_type      | Default |          |           | &#10003;      |
| dns-response    | duration         |         |          |           | &#10003;      |
|                 | rule             |         |          |           | &#10003;      |
|                 | location         |         |          |           | &#10003;      |
|                 | category         | Legacy  |          | &#10003;  |               |
|                 | department       |         |          |           | &#10003;      |
| http-session    | risk_level       | Default |          |           | &#10003;      |
|                 | location         | Default |          |           | &#10003;      |
| network-session | app              | Default |          |           | &#10003;      |
|                 | ca_runtime       | Default |          |           | &#10003;      |
|                 | host_ip          | Default |          |           | &#10003;      |
|                 | host_bytes_out   | Default |          |           | &#10003;      |
|                 | bytes_in         | Default |          |           | &#10003;      |
|                 | policy_name      | Default |          |           | &#10003;      |
|                 | session_id       | Default |          |           | &#10003;      |
|                 | app_group        | Default |          |           | &#10003;      |
|                 | host_zen_code    | Default |          |           | &#10003;      |
|                 | session_start    | Default |          |           | &#10003;      |
|                 | src_zen_code     | Default |          |           | &#10003;      |
|                 | bytes_out        | Default |          |           | &#10003;      |
|                 | connection_id    | Default |          |           | &#10003;      |
|                 | src_country      | Default |          |           | &#10003;      |
|                 | host_bytes_in    | Default |          |           | &#10003;      |
|                 | app_learntime    | Default |          |           | &#10003;      |
|                 | policy_runtime   | Default |          |           | &#10003;      |
|                 | session_end      | Default |          |           | &#10003;      |
|                 | direction        | Default |          |           | &#10003;      |

