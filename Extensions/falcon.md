falcon
======

Expression
----------

product = falcon

Fields
------

| Field | Core     | Detection | Informational |
| ----- | -------- | --------- | ------------- |
| user  | &#10003; | &#10003;  |               |
| aid   |          |           | &#10003;      |

Activity Types
--------------

| Activity Type             | Field                           | Status  | Core     | Detection | Informational |
| ------------------------- | ------------------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger             | indicator                       |         |          |           |               |
|                           | file_path                       | Legacy  |          |           | &#10003;      |
|                           | grandparent_command_line        |         |          |           |               |
|                           | rooting                         |         |          |           |               |
|                           | parent_process_command_line     |         |          |           |               |
|                           | falcon_host_link                |         |          |           |               |
|                           | kill_parent                     |         |          |           |               |
|                           | kill_process                    |         |          |           |               |
|                           | domain_user_name                |         |          |           |               |
|                           | pattern_disposition_description |         |          |           |               |
|                           | critical_process_disabled       |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | policy_disabled                 |         |          |           |               |
|                           | process_name                    | Legacy  |          | &#10003;  |               |
|                           | alert_id                        | Legacy  |          |           | &#10003;      |
|                           | hash_md5                        |         |          |           |               |
|                           | image_file_name                 |         |          |           |               |
|                           | sensor_only                     |         |          |           |               |
|                           | dest_port                       | Legacy  |          | &#10003;  |               |
|                           | process_blocked                 |         |          |           |               |
|                           | app                             |         |          |           |               |
|                           | registry_operation_blocked      |         |          |           |               |
|                           | bootup_safeguard_enabled        |         |          |           |               |
|                           | process_command_line            |         |          |           |               |
|                           | src_host                        | Legacy  | &#10003; | &#10003;  |               |
|                           | inddet_mask                     |         |          |           |               |
|                           | additional_info                 |         |          |           |               |
|                           | dest_ip                         | Legacy  | &#10003; | &#10003;  |               |
|                           | domain                          |         |          |           |               |
|                           | event_name                      |         |          |           |               |
|                           | process_path                    | Legacy  |          | &#10003;  |               |
|                           | aid                             |         |          |           |               |
|                           | process_id                      |         |          |           |               |
|                           | quarantine_machine              |         |          |           |               |
|                           | detect                          |         |          |           |               |
|                           | fs_operation_blocked            |         |          |           |               |
|                           | quarantine_file                 |         |          |           |               |
|                           | src_ip                          | Legacy  | &#10003; | &#10003;  |               |
|                           | sensor_id                       |         |          |           |               |
|                           | operation_blocked               |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | kill_sub_process                |         |          |           |               |
|                           | new_hash                        |         |          |           |               |
|                           | os                              |         |          |           |               |
|                           | file_name                       | Legacy  | &#10003; |           |               |
|                           | file_dir                        | Legacy  |          |           | &#10003;      |
|                           | target                          |         |          |           |               |
|                           | hash_sha256                     |         |          |           |               |
|                           | src_port                        | Legacy  |          |           | &#10003;      |
|                           | file_ext                        |         |          |           |               |
|                           | parent_image_filename           |         |          |           |               |
|                           | old_hash                        |         |          |           |               |
|                           | bytes                           | Legacy  |          | &#10003;  |               |
|                           | grandparent_image_filename      |         |          |           |               |
|                           | user_sid                        |         |          |           |               |
|                           | dest_host                       | Legacy  |          | &#10003;  |               |
|                           | parent_process_guid             |         |          |           |               |
|                           | user                            | Legacy  |          | &#10003;  |               |
| app-activity              | app                             | Default |          |           | &#10003;      |
|                           | src_ip                          | Default |          | &#10003;  |               |
|                           | resource                        | Default |          |           | &#10003;      |
|                           | additional_info                 | Default |          |           | &#10003;      |
|                           | domain                          | Default |          |           | &#10003;      |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Default |          | &#10003;  |               |
|                           | object                          | Default |          |           | &#10003;      |
| app-login                 | src_ip                          | Default |          | &#10003;  |               |
|                           | activity_details                | Default |          |           | &#10003;      |
|                           | event_name                      | Default |          |           | &#10003;      |
|                           | session_id                      | Default |          |           | &#10003;      |
| configuration-modify      | domain                          |         |          |           |               |
|                           | domain_user_name                |         |          |           |               |
|                           | operation                       |         |          |           |               |
|                           | user                            |         |          |           |               |
|                           | object                          |         |          |           |               |
| dns-request               | file_name                       |         |          |           |               |
|                           | alert_severity                  |         |          |           |               |
|                           | aip                             |         |          |           |               |
|                           | src_host                        | Legacy  | &#10003; | &#10003;  |               |
|                           | protocol                        |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | dns_response                    |         |          |           |               |
|                           | additional_info                 |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | domain                          |         |          |           |               |
|                           | hash_md5                        |         |          |           |               |
|                           | category                        |         |          |           |               |
|                           | alert_name                      |         |          |           |               |
| endpoint-login            | process_id                      | Default |          |           | &#10003;      |
|                           | file_path                       | Default |          |           | &#10003;      |
|                           | falcon_host_link                | Default |          |           | &#10003;      |
|                           | file_name                       | Default |          |           | &#10003;      |
|                           | file_dir                        | Default |          |           | &#10003;      |
|                           | aip                             | Default |          |           | &#10003;      |
|                           | session_id                      | Default |          |           | &#10003;      |
|                           | process_command_line            | Default |          |           | &#10003;      |
|                           | src_ip                          | Default |          | &#10003;  |               |
|                           | hash_sha256                     | Default |          |           | &#10003;      |
|                           | auth_package                    | Default |          |           | &#10003;      |
|                           | file_ext                        | Default |          |           | &#10003;      |
|                           | process_guid                    | Default |          |           | &#10003;      |
|                           | old_hash                        | Default |          |           | &#10003;      |
|                           | event_code                      | Default |          |           | &#10003;      |
|                           | bytes                           | Default |          |           | &#10003;      |
|                           | hash_md5                        | Default |          |           | &#10003;      |
|                           | user_sid                        | Default |          |           | &#10003;      |
|                           | event_name                      | Default |          |           | &#10003;      |
|                           | auth_server                     | Default |          |           | &#10003;      |
| file-delete               | process_id                      |         |          |           |               |
|                           | access                          | Legacy  |          | &#10003;  |               |
|                           | os                              |         |          |           |               |
|                           | falcon_host_link                |         |          |           |               |
|                           | session_id                      |         |          |           |               |
|                           | src_host                        | Legacy  |          | &#10003;  |               |
|                           | process_command_line            |         |          |           |               |
|                           | src_ip                          |         |          |           |               |
|                           | hash_sha256                     |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | old_hash                        |         |          |           |               |
|                           | bytes                           |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | alert_id                        |         |          |           |               |
|                           | hash_md5                        |         |          |           |               |
|                           | user_sid                        |         |          |           |               |
|                           | event_name                      |         |          |           |               |
|                           | alert_name                      |         |          |           |               |
| file-download             | src_port                        |         |          |           |               |
|                           | hash_sha256                     |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | old_hash                        |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | dest_ip                         |         |          |           |               |
|                           | event_name                      |         |          |           |               |
|                           | src_host                        | Legacy  |          |           | &#10003;      |
|                           | new_hash                        |         |          |           |               |
| file-read                 | process_id                      |         |          |           |               |
|                           | access                          | Legacy  |          | &#10003;  |               |
|                           | falcon_host_link                |         |          |           |               |
|                           | alert_severity                  |         |          |           |               |
|                           | src_ip                          |         |          |           |               |
|                           | protocol                        |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | alert_id                        |         |          |           |               |
|                           | hash_md5                        |         |          |           |               |
|                           | dest_port                       |         |          |           |               |
|                           | os                              |         |          |           |               |
|                           | session_id                      |         |          |           |               |
|                           | src_host                        | Legacy  |          | &#10003;  |               |
|                           | process_command_line            |         |          |           |               |
|                           | src_port                        |         |          |           |               |
|                           | hash_sha256                     |         |          |           |               |
|                           | additional_info                 |         |          |           |               |
|                           | old_hash                        |         |          |           |               |
|                           | bytes                           | Legacy  |          |           | &#10003;      |
|                           | domain                          |         |          |           |               |
|                           | dest_ip                         |         |          |           |               |
|                           | user_sid                        |         |          |           |               |
|                           | event_name                      |         |          |           |               |
|                           | category                        |         |          |           |               |
|                           | alert_name                      |         |          |           |               |
|                           | object                          |         |          |           |               |
| file-write                | process_id                      |         |          |           |               |
|                           | access                          | Legacy  |          | &#10003;  |               |
|                           | falcon_host_link                |         |          |           |               |
|                           | alert_severity                  |         |          |           |               |
|                           | src_ip                          |         |          |           |               |
|                           | protocol                        |         |          |           |               |
|                           | process_guid                    |         |          |           |               |
|                           | file_type                       | Legacy  |          |           | &#10003;      |
|                           | event_code                      |         |          |           |               |
|                           | alert_id                        |         |          |           |               |
|                           | hash_md5                        |         |          |           |               |
|                           | dest_port                       |         |          |           |               |
|                           | new_hash                        |         |          |           |               |
|                           | device_id                       | Legacy  |          | &#10003;  |               |
|                           | os                              |         |          |           |               |
|                           | session_id                      |         |          |           |               |
|                           | src_host                        |         |          |           |               |
|                           | process_command_line            |         |          |           |               |
|                           | src_port                        |         |          |           |               |
|                           | hash_sha256                     |         |          |           |               |
|                           | additional_info                 |         |          |           |               |
|                           | old_hash                        |         |          |           |               |
|                           | bytes                           | Legacy  |          | &#10003;  |               |
|                           | domain                          |         |          |           |               |
|                           | dest_ip                         |         |          |           |               |
|                           | user_sid                        |         |          |           |               |
|                           | event_name                      |         |          |           |               |
|                           | category                        |         |          |           |               |
|                           | alert_name                      |         |          |           |               |
| group-member-add          | src_ip                          |         |          |           |               |
|                           | domain                          | Legacy  |          |           | &#10003;      |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation                       |         |          |           |               |
| network-traffic           | process_guid                    | Default |          |           | &#10003;      |
|                           | additional_info                 | Default |          |           | &#10003;      |
|                           | file_name                       | Default |          |           | &#10003;      |
|                           | event_code                      | Default |          |           | &#10003;      |
|                           | process_name                    | Default |          |           | &#10003;      |
|                           | domain                          | Default |          |           | &#10003;      |
|                           | alert_severity                  | Default |          |           | &#10003;      |
|                           | hash_md5                        | Default |          |           | &#10003;      |
|                           | src_host                        | Default |          | &#10003;  |               |
|                           | category                        | Default |          |           | &#10003;      |
|                           | alert_name                      | Default |          |           | &#10003;      |
|                           | direction                       | Default |          |           | &#10003;      |
| peripheral_storage-insert | process_id                      |         |          |           |               |
|                           | file_path                       |         |          |           |               |
|                           | device_product                  |         |          |           | &#10003;      |
|                           | file_name                       |         |          |           |               |
|                           | activity_details                |         |          |           |               |
|                           | file_dir                        |         |          |           |               |
|                           | device_description              |         |          |           | &#10003;      |
|                           | src_ip                          |         |          |           |               |
|                           | file_ext                        |         |          |           |               |
|                           | event_code                      |         |          |           |               |
|                           | device_pid                      |         |          |           | &#10003;      |
|                           | vendor_id                       |         |          |           |               |
|                           | alert_id                        |         |          |           |               |
|                           | device_class                    |         |          |           | &#10003;      |
|                           | device_vendor                   |         |          |           | &#10003;      |
|                           | device_vid                      |         |          |           | &#10003;      |
|                           | operation                       |         |          |           |               |
| peripheral_storage-remove | file_path                       |         |          |           |               |
|                           | device_product                  |         |          |           | &#10003;      |
|                           | file_name                       | Legacy  | &#10003; |           |               |
|                           | activity_details                |         |          |           |               |
|                           | file_dir                        |         |          |           |               |
|                           | device_description              |         |          |           | &#10003;      |
|                           | src_ip                          |         |          |           |               |
|                           | file_ext                        |         |          |           |               |
|                           | event_code                      | Legacy  |          |           | &#10003;      |
|                           | device_pid                      |         |          |           | &#10003;      |
|                           | alert_id                        |         |          |           |               |
|                           | device_class                    |         |          |           | &#10003;      |
|                           | device_vendor                   |         |          |           | &#10003;      |
|                           | device_vid                      |         |          |           | &#10003;      |
|                           | operation                       |         |          |           |               |
| process-create            | file_path                       | Default |          |           | &#10003;      |
|                           | os                              | Default |          |           | &#10003;      |
|                           | falcon_host_link                | Default |          |           | &#10003;      |
|                           | file_name                       | Default |          |           | &#10003;      |
|                           | service_name                    | Default |          |           | &#10003;      |
|                           | file_dir                        | Default |          |           | &#10003;      |
|                           | session_id                      | Default |          |           | &#10003;      |
|                           | process_command_line            | Default |          |           | &#10003;      |
|                           | hash_sha256                     | Default |          |           | &#10003;      |
|                           | src_ip                          | Default |          | &#10003;  |               |
|                           | log_severity                    | Default |          |           | &#10003;      |
|                           | process_guid                    | Default |          |           | &#10003;      |
|                           | file_ext                        | Default |          |           | &#10003;      |
|                           | grandparent_process_path        | Default |          |           | &#10003;      |
|                           | additional_info                 | Default |          |           | &#10003;      |
|                           | old_hash                        | Default |          |           | &#10003;      |
|                           | event_code                      | Default |          |           | &#10003;      |
|                           | bytes                           | Default |          |           | &#10003;      |
|                           | dest_ip                         | Default |          | &#10003;  |               |
|                           | hash_md5                        | Default |          |           | &#10003;      |
|                           | user_sid                        | Default |          |           | &#10003;      |
|                           | parent_process_guid             | Default |          |           | &#10003;      |
| scheduled_task-create     | src_ip                          |         |          |           |               |
|                           | file_path                       |         |          |           |               |
|                           | file_ext                        |         |          |           |               |
|                           | event_code                      | Legacy  |          |           | &#10003;      |
|                           | file_name                       |         |          |           |               |
|                           | file_dir                        |         |          |           |               |
| user-create               | src_ip                          |         |          |           |               |
|                           | app                             |         |          |           |               |
|                           | domain                          | Legacy  |          |           | &#10003;      |
|                           | event_name                      |         |          |           |               |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation                       |         |          |           |               |
| user-delete               | src_ip                          |         |          |           |               |
|                           | app                             |         |          |           |               |
|                           | domain                          | Legacy  |          |           | &#10003;      |
|                           | event_name                      |         |          |           |               |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation                       |         |          |           |               |
| user-modify               | src_ip                          |         |          |           |               |
|                           | app                             |         |          |           |               |
|                           | domain                          | Legacy  |          |           | &#10003;      |
|                           | event_name                      |         |          |           |               |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Legacy  | &#10003; |           |               |
|                           | operation                       |         |          |           |               |
| user-role-assign          | src_ip                          | Default |          | &#10003;  |               |
|                           | app                             | Default |          |           | &#10003;      |
|                           | domain                          | Default |          |           | &#10003;      |
|                           | event_name                      | Default |          |           | &#10003;      |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Default |          | &#10003;  |               |
|                           | operation                       | Default |          |           | &#10003;      |
| user-role-revoke          | src_ip                          | Default |          | &#10003;  |               |
|                           | app                             | Default |          |           | &#10003;      |
|                           | domain                          | Default |          |           | &#10003;      |
|                           | event_name                      | Default |          |           | &#10003;      |
|                           | domain_user_name                |         |          |           |               |
|                           | user                            | Default |          | &#10003;  |               |
|                           | operation                       | Default |          |           | &#10003;      |

