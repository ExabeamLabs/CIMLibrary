unix
====

Expression
----------

product = unix

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field                 | Status  | Core     | Detection | Informational |
| ----------------------- | --------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger           | parent_process_id     |         |          |           |               |
|                         | file_path             | Legacy  |          |           | &#10003;      |
|                         | process_id            |         |          |           |               |
|                         | operation_type        |         |          |           |               |
|                         | service_name          |         |          |           |               |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           |               |
|                         | process_command_line  |         |          |           |               |
|                         | src_host              | Legacy  | &#10003; | &#10003;  |               |
|                         | event_subtype         |         |          |           |               |
|                         | event_category        |         |          |           |               |
|                         | result                |         |          |           |               |
|                         | src_ip                | Legacy  | &#10003; | &#10003;  |               |
|                         | path                  |         |          |           |               |
|                         | group_id              |         |          |           |               |
|                         | process_name          | Legacy  |          | &#10003;  |               |
|                         | arg                   |         |          |           |               |
|                         | dest_host             | Legacy  |          | &#10003;  |               |
|                         | user                  | Legacy  |          | &#10003;  |               |
| email-receive           | protocol              | Default |          |           | &#10003;      |
|                         | bytes                 | Default |          |           | &#10003;      |
|                         | num_recipients        | Default |          |           | &#10003;      |
| email-send              | bytes                 | Default |          |           | &#10003;      |
| endpoint-authentication | src_ip                | Default |          | &#10003;  |               |
|                         | process_id            | Default |          |           | &#10003;      |
|                         | auth_method           | Default |          |           | &#10003;      |
|                         | operation_type        | Default |          |           | &#10003;      |
|                         | group_id              | Default |          |           | &#10003;      |
|                         | process_name          | Default |          |           | &#10003;      |
|                         | dest_ip               | Default |          | &#10003;  |               |
|                         | file_owner            | Default |          |           | &#10003;      |
|                         | src_host              | Default |          | &#10003;  |               |
|                         | process_command_line  | Default |          |           | &#10003;      |
|                         | event_category        | Default |          |           | &#10003;      |
| endpoint-login          | parent_process_id     | Default |          |           | &#10003;      |
|                         | login_id              | Default |          |           | &#10003;      |
|                         | file_path             | Default |          |           | &#10003;      |
|                         | process_id            | Default |          |           | &#10003;      |
|                         | operation_type        | Default |          |           | &#10003;      |
|                         | auth                  | Default |          |           | &#10003;      |
|                         | service_name          | Default |          |           | &#10003;      |
|                         | file_owner            | Default |          |           | &#10003;      |
|                         | session_id            | Default |          |           | &#10003;      |
|                         | process_dir           | Default |          |           | &#10003;      |
|                         | process_command_line  | Default |          |           | &#10003;      |
|                         | src_host              | Default |          | &#10003;  |               |
|                         | event_category        | Default |          |           | &#10003;      |
|                         | src_port              | Default |          |           | &#10003;      |
|                         | src_ip                | Default |          | &#10003;  |               |
|                         | group_id              | Default |          |           | &#10003;      |
|                         | user_id               | Default |          |           | &#10003;      |
|                         | event_code            | Default |          |           | &#10003;      |
|                         | process_name          | Default |          |           | &#10003;      |
|                         | dest_ip               | Default |          | &#10003;  |               |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | dest_port             | Default |          |           | &#10003;      |
| file-delete             | dest_ip               |         |          |           |               |
| file-permission-modify  | parent_process_id     |         |          |           | &#10003;      |
|                         | process_id            |         |          | &#10003;  |               |
|                         | access                | Legacy  |          | &#10003;  |               |
|                         | operation_type        |         |          |           | &#10003;      |
|                         | service_name          |         |          |           | &#10003;      |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           | &#10003;      |
|                         | process_command_line  |         |          |           | &#10003;      |
|                         | src_host              |         |          | &#10003;  |               |
|                         | event_subtype         |         |          |           | &#10003;      |
|                         | event_category        |         |          |           | &#10003;      |
|                         | src_ip                |         |          | &#10003;  |               |
|                         | group_id              |         |          |           | &#10003;      |
|                         | user_id               |         |          |           | &#10003;      |
|                         | bytes                 |         |          |           | &#10003;      |
|                         | process_name          | Legacy  |          |           | &#10003;      |
|                         | operation             |         |          |           | &#10003;      |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
|                         | account               |         |          |           |               |
| file-read               | parent_process_id     |         |          |           | &#10003;      |
|                         | process_id            |         |          | &#10003;  |               |
|                         | access                | Legacy  |          | &#10003;  |               |
|                         | operation_type        |         |          |           | &#10003;      |
|                         | service_name          |         |          |           | &#10003;      |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           | &#10003;      |
|                         | process_command_line  |         |          |           | &#10003;      |
|                         | src_host              | Legacy  |          | &#10003;  |               |
|                         | event_subtype         |         |          |           | &#10003;      |
|                         | event_category        |         |          |           | &#10003;      |
|                         | src_ip                |         |          | &#10003;  |               |
|                         | group_id              |         |          |           | &#10003;      |
|                         | user_id               |         |          |           | &#10003;      |
|                         | bytes                 | Legacy  |          |           | &#10003;      |
|                         | process_name          | Legacy  |          |           | &#10003;      |
|                         | operation             |         |          |           | &#10003;      |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
|                         | account               |         |          |           |               |
| file-write              |                       |         |          |           |               |
| group-member-add        | src_ip                |         |          |           |               |
| group-member-remove     | parent_process_id     |         |          |           |               |
|                         | file_path             |         |          |           |               |
|                         | process_id            |         |          |           |               |
|                         | operation_type        |         |          |           |               |
|                         | service_name          |         |          |           |               |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           |               |
|                         | process_command_line  |         |          |           |               |
|                         | src_host              | Legacy  |          | &#10003;  |               |
|                         | event_category        |         |          |           |               |
|                         | src_ip                |         |          |           |               |
|                         | group_id              | Legacy  |          | &#10003;  |               |
|                         | user_id               |         |          |           |               |
|                         | process_name          |         |          |           |               |
|                         | dest_user_id          |         |          |           |               |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
| process-create          | process_relative_dir  | Default |          |           | &#10003;      |
|                         | operation_type        | Default |          |           | &#10003;      |
|                         | user_id               | Default |          |           | &#10003;      |
|                         | group_id              | Default |          |           | &#10003;      |
|                         | additional_info       | Default |          |           | &#10003;      |
|                         | current_working_dir   | Default |          |           | &#10003;      |
|                         | session_id            | Default |          |           | &#10003;      |
|                         | process_relative_path | Default |          |           | &#10003;      |
|                         | object                | Default |          |           | &#10003;      |
| user-create             | parent_process_id     |         |          |           |               |
|                         | file_path             |         |          |           |               |
|                         | process_id            |         |          |           |               |
|                         | operation_type        |         |          |           |               |
|                         | service_name          |         |          |           |               |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           |               |
|                         | process_command_line  |         |          |           |               |
|                         | src_host              | Legacy  |          | &#10003;  |               |
|                         | event_category        |         |          |           |               |
|                         | src_ip                |         |          |           |               |
|                         | group_id              |         |          |           |               |
|                         | user_id               |         |          |           |               |
|                         | process_name          |         |          |           |               |
|                         | dest_user_id          |         |          |           |               |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
| user-delete             | parent_process_id     |         |          |           |               |
|                         | file_path             |         |          |           |               |
|                         | process_id            |         |          |           |               |
|                         | operation_type        |         |          |           |               |
|                         | service_name          |         |          |           |               |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            |         |          |           |               |
|                         | process_command_line  |         |          |           |               |
|                         | src_host              |         |          |           |               |
|                         | event_category        |         |          |           |               |
|                         | src_ip                |         |          |           |               |
|                         | group_id              |         |          |           |               |
|                         | user_id               |         |          |           |               |
|                         | process_name          |         |          |           |               |
|                         | dest_user_id          |         |          |           |               |
|                         | user                  | Legacy  | &#10003; | &#10003;  |               |
| user-lock               | src_ip                |         |          | &#10003;  |               |
|                         | auth_method           |         |          |           | &#10003;      |
|                         | event_code            |         |          |           | &#10003;      |
| user-password-modify    | parent_process_id     | Default |          |           | &#10003;      |
|                         | file_path             | Default |          |           | &#10003;      |
|                         | process_id            | Default |          |           | &#10003;      |
|                         | operation_type        | Default |          |           | &#10003;      |
|                         | service_name          | Default |          |           | &#10003;      |
|                         | local_user_name       |         |          |           |               |
|                         | file_owner            | Default |          |           | &#10003;      |
|                         | process_command_line  | Default |          |           | &#10003;      |
|                         | src_host              | Default |          | &#10003;  |               |
|                         | event_category        | Default |          |           | &#10003;      |
|                         | src_ip                | Default |          | &#10003;  |               |
|                         | group_id              | Default |          |           | &#10003;      |
|                         | user_id               | Default |          |           | &#10003;      |
|                         | process_name          | Default |          |           | &#10003;      |
|                         | dest_ip               | Default |          | &#10003;  |               |
|                         | dest_user_id          | Default |          |           | &#10003;      |
|                         | user                  | Default |          | &#10003;  |               |
| user-switch             | process_relative_dir  | Default |          |           | &#10003;      |
|                         | current_working_dir   | Default |          |           | &#10003;      |
|                         | process_relative_path | Default |          |           | &#10003;      |

