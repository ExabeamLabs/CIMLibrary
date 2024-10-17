event viewer - security
=======================

Expression
----------

product = "event viewer - security"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| login_id           |          |           | &#10003;      |
| event_id           |          |           | &#10003;      |
| log_name           | &#10003; |           |               |
| user_id            |          |           | &#10003;      |
| event_code         | &#10003; | &#10003;  |               |
| domain             |          | &#10003;  |               |
| event_name         |          |           | &#10003;      |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| src_host           | &#10003; | &#10003;  |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type             | Field                  | Status  | Core     | Detection | Informational |
| ------------------------- | ---------------------- | ------- | -------- | --------- | ------------- |
| audit_policy-modify       | policy_changes         |         |          | &#10003;  |               |
|                           | audit_subcategory      | Legacy  |          |           | &#10003;      |
|                           | audit_category         | Legacy  |          |           | &#10003;      |
| ds_object-create          |                        |         |          |           |               |
| ds_object-delete          |                        |         |          |           |               |
| ds_object-modify          | access                 | Default |          |           | &#10003;      |
|                           | access_mask            | Default |          |           | &#10003;      |
|                           | attribute              | Default |          |           | &#10003;      |
|                           | attribute_value        | Default |          |           | &#10003;      |
|                           | operation              | Default |          |           | &#10003;      |
| ds_object-move            |                        |         |          |           |               |
| ds_object-restore         |                        |         |          |           |               |
| endpoint-authentication   | src_ip                 | Default |          | &#10003;  |               |
|                           | src_port               | Default |          |           | &#10003;      |
|                           | ticket_options         | Default |          |           | &#10003;      |
|                           | ticket_encryption_type | Default |          |           | &#10003;      |
|                           | kerberos_service_name  | Default |          |           | &#10003;      |
| endpoint-delete           |                        |         |          |           |               |
| endpoint-domain-join      | process_id             |         |          |           | &#10003;      |
|                           | dest_user_sid          | Default |          |           | &#10003;      |
|                           | user_sid               |         |          |           |               |
| endpoint-lock             | session_id             |         |          |           | &#10003;      |
| endpoint-login            | result                 | Default |          |           | &#10003;      |
|                           | src_ip                 | Default |          | &#10003;  |               |
|                           | src_port               | Default |          |           | &#10003;      |
|                           | auth_package           | Default |          |           | &#10003;      |
|                           | process_id             | Default |          |           | &#10003;      |
|                           | sub_status             | Default |          |           | &#10003;      |
|                           | process_name           | Default |          |           | &#10003;      |
|                           | process_dir            | Default |          |           | &#10003;      |
|                           | process_path           | Default |          |           | &#10003;      |
|                           | auth_process           | Default |          |           | &#10003;      |
| endpoint-logout           | src_ip                 |         |          |           |               |
|                           | src_port               |         |          |           |               |
|                           | session_name           |         |          |           |               |
| endpoint-modify           | old_attribute          |         |          | &#10003;  |               |
|                           | new_attribute          |         |          | &#10003;  |               |
|                           | attribute              |         |          |           | &#10003;      |
| endpoint-unlock           | session_id             |         |          |           | &#10003;      |
| file-delete               | handle_id              |         |          |           | &#10003;      |
|                           | process_id             |         |          |           | &#10003;      |
|                           | login_id               |         |          |           |               |
|                           | access                 | Legacy  |          | &#10003;  |               |
|                           | access_mask            |         |          |           | &#10003;      |
|                           | process_name           | Legacy  |          |           | &#10003;      |
|                           | process_dir            | Legacy  |          |           | &#10003;      |
|                           | process_path           | Legacy  |          |           | &#10003;      |
|                           | object_id              |         |          |           |               |
|                           | object_class           |         |          |           |               |
|                           | object_server          |         |          |           |               |
|                           | object                 |         |          |           |               |
| file-read                 | handle_id              |         |          |           | &#10003;      |
|                           | process_id             |         |          |           | &#10003;      |
|                           | access                 | Legacy  |          | &#10003;  |               |
|                           | access_mask            |         |          |           | &#10003;      |
|                           | process_name           | Legacy  |          |           | &#10003;      |
|                           | process_dir            | Legacy  |          |           | &#10003;      |
|                           | process_path           | Legacy  |          | &#10003;  |               |
| file-write                | handle_id              |         |          |           | &#10003;      |
|                           | process_id             |         |          |           | &#10003;      |
|                           | access                 | Legacy  |          | &#10003;  |               |
|                           | access_mask            |         |          |           | &#10003;      |
|                           | process_name           | Legacy  |          |           | &#10003;      |
|                           | process_dir            | Legacy  |          |           | &#10003;      |
|                           | process_path           | Legacy  |          | &#10003;  |               |
| group-member-add          | member_id              |         |          |           | &#10003;      |
|                           | group_id               | Legacy  |          | &#10003;  |               |
| group-member-remove       | member_id              |         |          |           | &#10003;      |
|                           | group_id               | Legacy  |          | &#10003;  |               |
|                           | group_type             | Legacy  |          |           | &#10003;      |
| log-clear                 |                        |         |          |           |               |
| network-session           | process_id             | Default |          |           | &#10003;      |
|                           | process_name           | Default |          |           | &#10003;      |
|                           | process_dir            | Default |          |           | &#10003;      |
|                           | process_path           | Default |          |           | &#10003;      |
|                           | direction              | Default |          |           | &#10003;      |
| peripheral_storage-insert | device_product         |         |          |           | &#10003;      |
|                           | device_name            |         |          | &#10003;  |               |
|                           | compatible_id          |         |          |           | &#10003;      |
|                           | device_pid             |         |          |           | &#10003;      |
|                           | class_id               |         |          |           | &#10003;      |
|                           | vendor_id              |         |          |           | &#10003;      |
|                           | device_description     |         |          |           | &#10003;      |
|                           | device_class           |         |          |           | &#10003;      |
|                           | device_vendor          |         |          |           | &#10003;      |
|                           | device_vid             |         |          |           | &#10003;      |
|                           | class_name             |         |          | &#10003;  | &#10003;      |
|                           | location_information   |         |          |           | &#10003;      |
| process-create            | process_integrity      | Default |          |           | &#10003;      |
|                           | elevation_type         | Default |          |           | &#10003;      |
| scheduled_task-create     | file_path              |         |          | &#10003;  |               |
|                           | file_ext               |         |          | &#10003;  |               |
|                           | dest_domain_user_name  |         |          |           |               |
|                           | file_name              |         |          | &#10003;  |               |
|                           | file_dir               |         |          | &#10003;  |               |
|                           | dest_domain            |         |          | &#10003;  |               |
|                           | description            | Legacy  |          |           | &#10003;      |
|                           | dest_user              |         |          | &#10003;  |               |
|                           | dest_user_id           |         |          |           | &#10003;      |
|                           | triggers               | Legacy  |          |           | &#10003;      |
|                           | run_level              | Legacy  |          |           | &#10003;      |
| service-create            | file_path              |         |          | &#10003;  |               |
|                           | service_command_line   |         |          | &#10003;  |               |
|                           | service_type           |         |          | &#10003;  |               |
|                           | file_ext               |         |          | &#10003;  |               |
|                           | dest_domain_user_name  |         |          |           |               |
|                           | file_name              |         |          | &#10003;  |               |
|                           | file_dir               |         |          | &#10003;  |               |
|                           | dest_domain            |         |          | &#10003;  |               |
|                           | service_start_type     | Legacy  |          |           | &#10003;      |
|                           | dest_user              |         |          |           |               |
|                           | dest_user_id           |         |          |           | &#10003;      |
| share-access              | task_name              | Default |          |           | &#10003;      |
|                           | process_id             | Default |          |           | &#10003;      |
|                           | privileges             | Default |          |           | &#10003;      |
|                           | access                 | Default |          |           | &#10003;      |
|                           | login_type             | Default |          |           | &#10003;      |
|                           | sid_history            | Default |          |           | &#10003;      |
|                           | dest_user_sid          | Default |          |           | &#10003;      |
|                           | src_ip                 | Default |          | &#10003;  |               |
|                           | thread_id              | Default |          |           | &#10003;      |
|                           | process_guid           | Default |          |           | &#10003;      |
|                           | dest_domain_user_name  |         |          |           |               |
|                           | file_type              | Default |          |           | &#10003;      |
|                           | process_name           | Default |          |           | &#10003;      |
|                           | key_length             | Default |          |           | &#10003;      |
|                           | operation_id           | Default |          |           | &#10003;      |
|                           | provider_name          | Default |          |           | &#10003;      |
|                           | auth_process           | Default |          |           | &#10003;      |
|                           | service_name           | Default |          |           | &#10003;      |
|                           | file_name              | Default |          |           | &#10003;      |
|                           | file_dir               | Default |          |           | &#10003;      |
|                           | process_dir            | Default |          |           | &#10003;      |
|                           | dest_user              | Default |          | &#10003;  |               |
|                           | process_command_line   | Default |          |           | &#10003;      |
|                           | object_server          | Default |          |           | &#10003;      |
|                           | src_port               | Default |          |           | &#10003;      |
|                           | auth_package           | Default |          |           | &#10003;      |
|                           | service_type           | Default |          |           | &#10003;      |
|                           | file_ext               | Default |          |           | &#10003;      |
|                           | additional_info        | Default |          |           | &#10003;      |
|                           | dest_ip                | Default |          | &#10003;  |               |
|                           | user_sid               | Default |          |           | &#10003;      |
|                           | dest_domain            | Default |          |           | &#10003;      |
|                           | dest_host              | Default |          | &#10003;  |               |
|                           | process_path           | Default |          |           | &#10003;      |
|                           | object                 | Default |          |           | &#10003;      |
| share-create              | src_ip                 | Legacy  |          | &#10003;  |               |
|                           | src_port               | Legacy  |          | &#10003;  |               |
|                           | d_name                 |         |          |           |               |
|                           | d_parent               |         |          |           |               |
|                           | dest_ip                |         |          |           |               |
|                           | dest_host              | Legacy  | &#10003; | &#10003;  |               |
|                           | aid                    |         |          |           |               |
| share-delete              | src_ip                 | Legacy  |          | &#10003;  |               |
|                           | src_port               | Legacy  |          | &#10003;  |               |
|                           | dest_ip                |         |          |           |               |
|                           | user_sid               |         |          |           |               |
|                           | dest_host              | Legacy  | &#10003; | &#10003;  |               |
| share-modify              | src_ip                 | Legacy  |          | &#10003;  |               |
|                           | src_port               | Legacy  |          | &#10003;  |               |
|                           | dest_ip                |         |          |           |               |
|                           | user_sid               |         |          |           |               |
|                           | dest_host              | Legacy  | &#10003; | &#10003;  |               |
| user-create               | dest_user_type         |         |          |           | &#10003;      |
|                           | domain_controller      |         |          |           | &#10003;      |
|                           | dest_user_id           |         |          |           | &#10003;      |
| user-delete               | dest_user_id           |         |          |           | &#10003;      |
| user-disable              | dest_user_id           |         |          |           | &#10003;      |
| user-enable               | dest_user_id           |         |          |           | &#10003;      |
| user-lock                 | dest_user_id           |         |          |           | &#10003;      |
| user-modify               | old_attribute          |         |          | &#10003;  |               |
|                           | new_attribute          |         |          | &#10003;  |               |
|                           | attribute              |         |          | &#10003;  |               |
| user-name-modify          | old_user_name          | Default |          |           | &#10003;      |
|                           | new_user_name          | Default |          |           | &#10003;      |
| user-password-modify      | dest_user_id           | Default |          |           | &#10003;      |
| user-password-reset       |                        |         |          |           |               |
| user-privilege-assign     |                        |         |          |           |               |
| user-privilege-use        | process_id             | Legacy  |          |           | &#10003;      |
|                           | object_type            | Legacy  |          |           | &#10003;      |
|                           | object_handle          |         |          |           | &#10003;      |
|                           | service_name           |         |          |           | &#10003;      |
|                           | process_name           | Legacy  | &#10003; | &#10003;  |               |
|                           | object_name            | Legacy  | &#10003; | &#10003;  |               |
|                           | process_dir            | Legacy  |          |           | &#10003;      |
|                           | process_path           | Legacy  |          | &#10003;  |               |
|                           | object_server          | Legacy  |          |           | &#10003;      |
| user-switch               | src_ip                 |         |          | &#10003;  |               |
|                           | src_port               |         |          |           | &#10003;      |
|                           | dest_login_id          |         |          |           | &#10003;      |
|                           | process_id             |         |          | &#10003;  |               |
|                           | process_name           |         |          | &#10003;  |               |
|                           | dest_service_name      |         |          |           | &#10003;      |
|                           | dest_host              |         |          |           |               |
|                           | process_dir            |         |          | &#10003;  |               |
|                           | dest_user_id           |         |          |           | &#10003;      |
|                           | process_path           |         |          | &#10003;  |               |
| user-unlock               | dest_user_id           |         |          |           | &#10003;      |

