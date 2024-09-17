carbon black app control
========================

Expression
----------

product = "carbon black app control"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; |           |               |

Activity Types
--------------

| Activity Type             | Field                       | Status  | Core | Detection | Informational |
| ------------------------- | --------------------------- | ------- | ---- | --------- | ------------- |
| app-login                 | src_ip                      | Default |      | &#10003;  |               |
|                           | dest_ip                     | Default |      | &#10003;  |               |
|                           | email_domain                | Default |      |           | &#10003;      |
| endpoint-lock             | src_ip                      |         |      | &#10003;  |               |
|                           | event_code                  |         |      |           | &#10003;      |
|                           | dest_ip                     |         |      | &#10003;  |               |
|                           | src_host                    |         |      | &#10003;  |               |
| endpoint-login            | src_ip                      | Default |      | &#10003;  |               |
|                           | event_code                  | Default |      |           | &#10003;      |
|                           | dest_ip                     | Default |      | &#10003;  |               |
|                           | src_host                    | Default |      | &#10003;  |               |
| endpoint-unlock           | src_ip                      |         |      | &#10003;  |               |
|                           | event_code                  | Legacy  |      |           | &#10003;      |
|                           | dest_ip                     |         |      | &#10003;  |               |
|                           | src_host                    |         |      | &#10003;  |               |
| file-delete               | parent_process_id           |         |      |           | &#10003;      |
|                           | process_id                  |         |      |           | &#10003;      |
|                           | parent_process_command_line |         |      | &#10003;  |               |
|                           | process_guid                |         |      |           | &#10003;      |
|                           | process_name                | Legacy  |      |           | &#10003;      |
|                           | alert_id                    |         |      |           | &#10003;      |
|                           | action                      |         |      | &#10003;  |               |
|                           | event_name                  |         |      | &#10003;  |               |
|                           | process_dir                 | Legacy  |      |           | &#10003;      |
|                           | parent_process_guid         |         |      |           | &#10003;      |
|                           | process_path                | Legacy  |      |           | &#10003;      |
|                           | process_command_line        |         |      | &#10003;  |               |
| file-read                 | parent_process_id           |         |      |           | &#10003;      |
|                           | process_id                  |         |      |           | &#10003;      |
|                           | parent_process_command_line |         |      | &#10003;  |               |
|                           | process_guid                |         |      |           | &#10003;      |
|                           | process_name                | Legacy  |      |           | &#10003;      |
|                           | alert_id                    |         |      |           | &#10003;      |
|                           | action                      |         |      | &#10003;  |               |
|                           | event_name                  |         |      | &#10003;  |               |
|                           | process_dir                 | Legacy  |      |           | &#10003;      |
|                           | parent_process_guid         |         |      |           | &#10003;      |
|                           | process_path                | Legacy  |      | &#10003;  |               |
|                           | process_command_line        |         |      | &#10003;  |               |
| file-write                | parent_process_id           |         |      |           | &#10003;      |
|                           | process_id                  |         |      |           | &#10003;      |
|                           | parent_process_command_line |         |      | &#10003;  |               |
|                           | alert_severity              |         |      | &#10003;  |               |
|                           | process_dir                 | Legacy  |      |           | &#10003;      |
|                           | process_command_line        |         |      | &#10003;  |               |
|                           | src_host                    |         |      | &#10003;  |               |
|                           | src_ip                      |         |      | &#10003;  |               |
|                           | process_guid                |         |      |           | &#10003;      |
|                           | file_hash                   |         |      | &#10003;  |               |
|                           | additional_info             |         |      |           | &#10003;      |
|                           | process_name                | Legacy  |      |           | &#10003;      |
|                           | file_type                   | Legacy  |      |           | &#10003;      |
|                           | event_code                  |         |      |           | &#10003;      |
|                           | alert_id                    |         |      |           | &#10003;      |
|                           | action                      |         |      | &#10003;  |               |
|                           | event_name                  |         |      | &#10003;  |               |
|                           | parent_process_guid         |         |      |           | &#10003;      |
|                           | process_path                | Legacy  |      | &#10003;  |               |
|                           | policy                      |         |      | &#10003;  |               |
| network-session           | parent_process_id           | Default |      |           | &#10003;      |
|                           | process_id                  | Default |      |           | &#10003;      |
|                           | parent_process_command_line | Default |      |           | &#10003;      |
|                           | process_dir                 | Default |      |           | &#10003;      |
|                           | process_command_line        | Default |      |           | &#10003;      |
|                           | sensor_id                   | Default |      |           | &#10003;      |
|                           | process_guid                | Default |      |           | &#10003;      |
|                           | web_domain                  | Default |      |           | &#10003;      |
|                           | process_name                | Default |      |           | &#10003;      |
|                           | alert_id                    | Default |      |           | &#10003;      |
|                           | hash_md5                    | Default |      |           | &#10003;      |
|                           | action                      | Default |      |           | &#10003;      |
|                           | event_name                  | Default |      |           | &#10003;      |
|                           | parent_process_guid         | Default |      |           | &#10003;      |
|                           | process_path                | Default |      |           | &#10003;      |
| peripheral_storage-insert | device_product              |         |      |           | &#10003;      |
|                           | activity_details            |         |      |           | &#10003;      |
|                           | device_description          |         |      |           | &#10003;      |
|                           | process_dir                 |         |      | &#10003;  |               |
|                           | event_code                  |         |      |           | &#10003;      |
|                           | process_name                | Legacy  |      |           | &#10003;      |
|                           | device_pid                  |         |      |           | &#10003;      |
|                           | dest_ip                     |         |      | &#10003;  |               |
|                           | event_name                  |         |      |           | &#10003;      |
|                           | device_class                |         |      |           | &#10003;      |
|                           | process_path                | Legacy  |      |           | &#10003;      |
|                           | device_vendor               |         |      |           | &#10003;      |
|                           | device_vid                  |         |      |           | &#10003;      |
| peripheral_storage-remove | device_product              |         |      |           | &#10003;      |
|                           | activity_details            |         |      |           | &#10003;      |
|                           | device_pid                  |         |      |           | &#10003;      |
|                           | dest_ip                     |         |      | &#10003;  |               |
|                           | device_description          |         |      |           | &#10003;      |
|                           | event_name                  |         |      |           | &#10003;      |
|                           | device_class                |         |      |           | &#10003;      |
|                           | device_vendor               |         |      |           | &#10003;      |
|                           | device_vid                  |         |      |           | &#10003;      |
| process-create            | sensor_id                   | Default |      |           | &#10003;      |
|                           | file_path                   | Default |      |           | &#10003;      |
|                           | process_guid                | Default |      |           | &#10003;      |
|                           | additional_info             | Default |      |           | &#10003;      |
|                           | file_name                   | Default |      |           | &#10003;      |
|                           | alert_id                    | Default |      |           | &#10003;      |
|                           | hash_md5                    | Default |      |           | &#10003;      |
|                           | arg                         | Default |      |           | &#10003;      |
|                           | dest_ip                     | Default |      | &#10003;  |               |
|                           | action                      | Default |      |           | &#10003;      |
|                           | event_name                  | Default |      |           | &#10003;      |
|                           | policy                      | Default |      |           | &#10003;      |

