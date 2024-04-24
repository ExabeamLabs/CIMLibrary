oracle access manager
=====================

Expression
----------

product = "oracle access manager"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          |           | &#10003;      |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field       | Status  | Core | Detection | Informational |
| ------------- | ----------- | ------- | ---- | --------- | ------------- |
| app-activity  | src_ip      | Default |      | &#10003;  |               |
|               | resource    | Default |      |           | &#10003;      |
|               | object      | Default |      |           | &#10003;      |
| app-login     | src_ip      | Default |      | &#10003;  |               |
|               | auth_method | Default |      |           | &#10003;      |
|               | resource    | Default |      |           | &#10003;      |
|               | dest_ip     | Default |      | &#10003;  |               |
|               | dest_host   | Default |      | &#10003;  |               |
|               | object      | Default |      |           | &#10003;      |

