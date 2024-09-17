digital guardian endpoint protection
====================================

Expression
----------

product = "digital guardian endpoint protection"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| event_code       |          |           | &#10003;      |
| domain           |          |           | &#10003;      |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type             | Field              | Status  | Core     | Detection | Informational |
| ------------------------- | ------------------ | ------- | -------- | --------- | ------------- |
| app-login                 | app                | Default |          |           | &#10003;      |
| email-send                | src_ip             | Default |          | &#10003;  |               |
|                           | bytes              | Default |          |           | &#10003;      |
|                           | dest_ip            | Default |          | &#10003;  |               |
|                           | dest_host          | Default |          | &#10003;  |               |
| endpoint-login            | process_name       | Default |          |           | &#10003;      |
| file-copy                 | process_name       | Default |          |           | &#10003;      |
|                           | src_host           | Default |          | &#10003;  |               |
| file-delete               | src_ip             |         |          | &#10003;  |               |
|                           | src_file_name      |         |          |           | &#10003;      |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              |         |          |           | &#10003;      |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | src_file_dir       |         |          |           | &#10003;      |
|                           | src_host           | Legacy  |          | &#10003;  |               |
| file-download             | src_ip             |         |          | &#10003;  |               |
|                           | src_port           |         |          |           | &#10003;      |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              | Legacy  |          | &#10003;  |               |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | dest_host          | Legacy  |          |           | &#10003;      |
|                           | dest_port          |         |          |           | &#10003;      |
| file-read                 | src_ip             |         |          | &#10003;  |               |
|                           | src_file_name      |         |          |           | &#10003;      |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              | Legacy  |          |           | &#10003;      |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | src_file_dir       |         |          |           | &#10003;      |
|                           | src_host           | Legacy  |          | &#10003;  |               |
| file-upload               | src_ip             |         |          | &#10003;  |               |
|                           | src_port           |         |          |           | &#10003;      |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              |         |          |           | &#10003;      |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | src_host           | Legacy  |          |           | &#10003;      |
|                           | dest_port          |         |          |           | &#10003;      |
| file-write                | src_ip             |         |          | &#10003;  |               |
|                           | src_file_name      | Legacy  |          | &#10003;  |               |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              | Legacy  |          | &#10003;  |               |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | src_file_dir       | Legacy  |          | &#10003;  |               |
|                           | src_host           |         |          | &#10003;  |               |
| network-session           | process_name       | Default |          |           | &#10003;      |
| peripheral_storage-insert | device_product     |         |          |           | &#10003;      |
|                           | rule_action        |         |          |           | &#10003;      |
|                           | os                 |         |          |           | &#10003;      |
|                           | file_name          |         |          |           | &#10003;      |
|                           | file_dir           |         |          |           | &#10003;      |
|                           | device_description |         |          |           | &#10003;      |
|                           | rule               |         |          |           | &#10003;      |
|                           | policy_name        |         |          |           | &#10003;      |
|                           | process_name       | Legacy  |          |           | &#10003;      |
|                           | bytes              |         |          |           | &#10003;      |
|                           | device_pid         |         |          |           | &#10003;      |
|                           | device_class       |         |          |           | &#10003;      |
|                           | device_vendor      |         |          |           | &#10003;      |
|                           | device_vid         |         |          |           | &#10003;      |
| printer-activity          | bytes              | Legacy  |          | &#10003;  |               |
|                           | dest_ip            |         |          | &#10003;  |               |
|                           | printer_name       | Legacy  | &#10003; | &#10003;  |               |
|                           | src_host           | Legacy  |          |           | &#10003;      |
|                           | object             |         |          |           | &#10003;      |
| process-create            | dest_ip            | Default |          | &#10003;  |               |

