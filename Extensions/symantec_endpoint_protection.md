symantec endpoint protection
============================

Expression
----------

product = symantec endpoint protection

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field            | Status  | Core     | Detection | Informational |
| ------------- | ---------------- | ------- | -------- | --------- | ------------- |
| alert-trigger | process_id       |         |          |           |               |
|               | os               |         |          |           |               |
|               | dest_mac         |         |          |           |               |
|               | process_dir      |         |          |           |               |
|               | domain_user_name |         |          |           |               |
|               | src_host         | Legacy  | &#10003; | &#10003;  |               |
|               | product_name     |         |          |           |               |
|               | src_ip           | Legacy  | &#10003; | &#10003;  |               |
|               | src_port         | Legacy  |          |           | &#10003;      |
|               | protocol         | Legacy  |          | &#10003;  |               |
|               | process_guid     |         |          |           |               |
|               | additional_info  |         |          |           |               |
|               | process_name     | Legacy  |          | &#10003;  |               |
|               | dest_ip          | Legacy  | &#10003; | &#10003;  |               |
|               | domain           |         |          |           |               |
|               | os_revision      |         |          |           |               |
|               | action           | Legacy  |          |           | &#10003;      |
|               | dest_host        | Legacy  |          | &#10003;  |               |
|               | process_path     | Legacy  |          | &#10003;  |               |
|               | user             | Legacy  |          | &#10003;  |               |
|               | dest_port        | Legacy  |          | &#10003;  |               |
|               | user_agent       |         |          |           |               |
| endpoint-scan | src_ip           | Default |          | &#10003;  |               |
|               | group_name       | Default |          |           | &#10003;      |
|               | domain           | Default |          |           | &#10003;      |
|               | domain_user_name |         |          |           |               |
|               | scan_id          | Default |          |           | &#10003;      |
|               | user             | Default |          | &#10003;  |               |

