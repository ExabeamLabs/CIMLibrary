forcepoint casb
===============

Expression
----------

product = "forcepoint casb"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| src_ip           |          | &#10003;  |               |
| result           |          |           | &#10003;      |
| domain           |          | &#10003;  |               |
| dest_ip          |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |
| user_agent       |          | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field            | Status  | Core     | Detection | Informational |
| ------------- | ---------------- | ------- | -------- | --------- | ------------- |
| alert-trigger | src_ip           | Legacy  | &#10003; | &#10003;  |               |
|               | additional_info  |         |          |           |               |
|               | dest_ip          | Legacy  | &#10003; | &#10003;  |               |
|               | domain           |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | user             | Legacy  |          | &#10003;  |               |
| app-activity  | privileges       | Default |          |           | &#10003;      |
|               | object           | Default |          |           | &#10003;      |
| app-login     | privileges       | Default |          |           | &#10003;      |

