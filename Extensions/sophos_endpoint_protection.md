sophos endpoint protection
==========================

Expression
----------

product = sophos endpoint protection

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          | &#10003;  |               |
| alert_id         |          |           | &#10003;      |
| domain_user_name |          |           |               |
| src_host         | &#10003; |           |               |
| user             | &#10003; | &#10003;  |               |
| alert_type       |          |           | &#10003;      |
| alert_name       |          |           | &#10003;      |

Activity Types
--------------

| Activity Type               | Field            | Status  | Core     | Detection | Informational |
| --------------------------- | ---------------- | ------- | -------- | --------- | ------------- |
| alert-trigger               | file_path        | Legacy  |          |           | &#10003;      |
|                             | access           |         |          |           |               |
|                             | device_id        |         |          |           |               |
|                             | file_name        | Legacy  | &#10003; |           |               |
|                             | file_dir         | Legacy  |          |           | &#10003;      |
|                             | domain_user_name |         |          |           |               |
|                             | src_host         | Legacy  | &#10003; | &#10003;  |               |
|                             | result           |         |          |           |               |
|                             | src_ip           | Legacy  | &#10003; | &#10003;  |               |
|                             | additional_info  |         |          |           |               |
|                             | alert_id         | Legacy  |          |           | &#10003;      |
|                             | dest_ip          | Legacy  | &#10003; | &#10003;  |               |
|                             | domain           |         |          |           |               |
|                             | dest_host        | Legacy  |          | &#10003;  |               |
|                             | malware_url      |         |          |           |               |
|                             | user             | Legacy  |          | &#10003;  |               |
| http-session                | malware_url      | Default |          |           | &#10003;      |
|                             | src_host         | Default |          | &#10003;  |               |
| network-session             |                  |         |          |           |               |
| peripheral_storage-activity | src_ip           | Default |          | &#10003;  |               |
|                             | bytes            | Default |          |           | &#10003;      |
|                             | file_name        | Default |          |           | &#10003;      |
| peripheral_storage-insert   | src_ip           |         |          |           |               |

