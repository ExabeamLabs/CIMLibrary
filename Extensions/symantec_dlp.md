symantec dlp
============

Expression
----------

product = "symantec dlp"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| src_ip           |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| src_host         | &#10003; | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type               | Field              | Status  | Core     | Detection | Informational |
| --------------------------- | ------------------ | ------- | -------- | --------- | ------------- |
| alert-trigger               | email_id           |         |          |           |               |
|                             | file_path          | Legacy  |          |           | &#10003;      |
|                             | local_user_name    |         |          |           |               |
|                             | device_type        |         |          |           |               |
|                             | result             |         |          |           |               |
|                             | src_ip             | Legacy  | &#10003; | &#10003;  |               |
|                             | external_address   |         |          |           |               |
|                             | protocol           | Legacy  |          | &#10003;  |               |
|                             | process_name       | Legacy  |          | &#10003;  |               |
|                             | alert_id           | Legacy  |          |           | &#10003;      |
|                             | occured_time       |         |          |           |               |
|                             | direction          |         |          |           |               |
|                             | email_attachment   |         |          |           |               |
|                             | device_id          |         |          |           |               |
|                             | os                 |         |          |           |               |
|                             | file_name          | Legacy  | &#10003; |           |               |
|                             | file_dir           | Legacy  |          |           | &#10003;      |
|                             | original_user      |         |          |           |               |
|                             | process_dir        |         |          |           |               |
|                             | src_host           | Legacy  | &#10003; | &#10003;  |               |
|                             | url                |         |          |           |               |
|                             | recorded_time      |         |          |           |               |
|                             | target             |         |          |           |               |
|                             | file_ext           |         |          |           |               |
|                             | additional_info    |         |          |           |               |
|                             | sender             | Legacy  | &#10003; |           |               |
|                             | web_domain         |         |          |           |               |
|                             | bytes              | Legacy  |          | &#10003;  |               |
|                             | recipients         |         |          |           |               |
|                             | dest_ip            | Legacy  | &#10003; | &#10003;  |               |
|                             | recipient          |         |          |           |               |
|                             | dest_host          | Legacy  |          | &#10003;  |               |
|                             | process_path       | Legacy  |          | &#10003;  |               |
|                             | operation          |         |          |           |               |
|                             | email_subject      |         |          |           |               |
|                             | user               | Legacy  |          | &#10003;  |               |
| file-delete                 | device_id          |         |          |           | &#10003;      |
|                             | bytes_in           |         |          | &#10003;  |               |
|                             | process_name       | Legacy  |          |           | &#10003;      |
|                             | process_dir        | Legacy  |          |           | &#10003;      |
|                             | device_type        |         |          | &#10003;  |               |
|                             | process_path       | Legacy  |          |           | &#10003;      |
| file-read                   | device_id          | Legacy  |          | &#10003;  |               |
|                             | bytes_in           |         |          | &#10003;  |               |
|                             | process_name       | Legacy  |          |           | &#10003;      |
|                             | process_dir        | Legacy  |          |           | &#10003;      |
|                             | device_type        | Legacy  |          |           | &#10003;      |
|                             | process_path       | Legacy  |          | &#10003;  |               |
| file-write                  | device_id          | Legacy  |          | &#10003;  |               |
|                             | bytes_in           |         |          | &#10003;  |               |
|                             | process_name       | Legacy  |          |           | &#10003;      |
|                             | process_dir        | Legacy  |          |           | &#10003;      |
|                             | device_type        | Legacy  |          |           | &#10003;      |
|                             | process_path       | Legacy  |          | &#10003;  |               |
| peripheral_storage-activity | file_path          | Default |          |           | &#10003;      |
|                             | device_product     |         |          |           | &#10003;      |
|                             | file_name          | Default |          |           | &#10003;      |
|                             | file_dir           | Default |          |           | &#10003;      |
|                             | device_description |         |          |           | &#10003;      |
|                             | process_dir        | Default |          |           | &#10003;      |
|                             | file_ext           | Default |          |           | &#10003;      |
|                             | process_name       | Default |          |           | &#10003;      |
|                             | bytes              | Default |          |           | &#10003;      |
|                             | device_pid         |         |          |           | &#10003;      |
|                             | device_class       |         |          |           | &#10003;      |
|                             | process_path       | Default |          |           | &#10003;      |
|                             | device_vendor      |         |          |           | &#10003;      |
|                             | device_vid         |         |          |           | &#10003;      |
| peripheral_storage-insert   | device_product     |         |          |           | &#10003;      |
|                             | device_pid         |         |          |           | &#10003;      |
|                             | device_description |         |          |           | &#10003;      |
|                             | device_class       |         |          |           | &#10003;      |
|                             | device_vendor      |         |          |           | &#10003;      |
|                             | device_vid         |         |          |           | &#10003;      |
|                             | operation_details  |         |          |           | &#10003;      |

