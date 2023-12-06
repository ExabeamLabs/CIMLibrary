microsoft 365 audit logs
========================

Expression
----------

product = "m365 audit logs"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |
| operation        |      |           | &#10003;      |

Activity Types
--------------

| Activity Type   | Field            | Status  | Core | Detection | Informational |
| --------------- | ---------------- | ------- | ---- | --------- | ------------- |
| app-activity    | src_ip           | Default |      | &#10003;  |               |
| app-login       | src_ip           | Default |      | &#10003;  |               |
|                 | additional_info  | Default |      |           | &#10003;      |
|                 | location_country | Default |      |           | &#10003;      |
|                 | location_city    | Default |      |           | &#10003;      |
|                 | result_code      | Default |      |           | &#10003;      |
|                 | src_host         | Default |      | &#10003;  |               |
|                 | location_state   | Default |      |           | &#10003;      |
| file-download   |                  |         |      |           |               |
| group-create    | src_ip           |         |      |           |               |
| group-delete    | src_ip           |         |      |           |               |
| policy-create   | src_ip           | Default |      | &#10003;  |               |
| policy-delete   | src_ip           | Default |      | &#10003;  |               |
| policy-modify   | src_ip           | Default |      | &#10003;  |               |
| policy-read     | src_ip           | Default |      | &#10003;  |               |
| share_link-open |                  |         |      |           |               |
| user-modify     | src_ip           |         |      |           |               |

