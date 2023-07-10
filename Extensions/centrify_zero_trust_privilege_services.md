centrify zero trust privilege services
======================================

Expression
----------

product = "centrify zero trust privilege services"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| event_name |      |           | &#10003;      |
| object     |      |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field            | Status  | Core     | Detection | Informational |
| -------------------- | ---------------- | ------- | -------- | --------- | ------------- |
| app-activity         | src_ip           | Default |          | &#10003;  |               |
|                      | auth_method      | Default |          |           | &#10003;      |
|                      | os               | Default |          |           | &#10003;      |
|                      | additional_info  | Default |          |           | &#10003;      |
|                      | dest_ip          | Default |          | &#10003;  |               |
|                      | domain           | Default |          |           | &#10003;      |
|                      | dest_host        | Default |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Default |          | &#10003;  |               |
|                      | user_agent       | Default |          |           | &#10003;      |
| role-create          | src_ip           | Default |          | &#10003;  |               |
|                      | os               | Default |          |           | &#10003;      |
|                      | additional_info  | Default |          |           | &#10003;      |
|                      | dest_ip          | Default |          | &#10003;  |               |
|                      | domain           | Default |          |           | &#10003;      |
|                      | dest_host        | Default |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Default |          | &#10003;  |               |
|                      | operation        | Default |          |           | &#10003;      |
|                      | user_agent       | Default |          |           | &#10003;      |
| role-delete          | src_ip           | Default |          | &#10003;  |               |
|                      | os               | Default |          |           | &#10003;      |
|                      | additional_info  | Default |          |           | &#10003;      |
|                      | dest_ip          | Default |          | &#10003;  |               |
|                      | domain           | Default |          |           | &#10003;      |
|                      | dest_host        | Default |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Default |          | &#10003;  |               |
|                      | operation        | Default |          |           | &#10003;      |
|                      | user_agent       | Default |          |           | &#10003;      |
| role-modify          | src_ip           | Default |          | &#10003;  |               |
|                      | os               | Default |          |           | &#10003;      |
|                      | additional_info  | Default |          |           | &#10003;      |
|                      | dest_ip          | Default |          | &#10003;  |               |
|                      | domain           | Default |          |           | &#10003;      |
|                      | dest_host        | Default |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Default |          | &#10003;  |               |
|                      | operation        | Default |          |           | &#10003;      |
|                      | user_agent       | Default |          |           | &#10003;      |
| user-create          | src_ip           |         |          |           |               |
|                      | os               |         |          |           |               |
|                      | additional_info  |         |          |           |               |
|                      | dest_ip          |         |          |           |               |
|                      | domain           | Legacy  |          |           | &#10003;      |
|                      | dest_host        | Legacy  |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Legacy  | &#10003; | &#10003;  |               |
|                      | operation        |         |          |           |               |
|                      | user_agent       |         |          |           |               |
| user-delete          | src_ip           |         |          |           |               |
|                      | os               |         |          |           |               |
|                      | additional_info  |         |          |           |               |
|                      | dest_ip          |         |          |           |               |
|                      | domain           | Legacy  |          |           | &#10003;      |
|                      | dest_host        | Legacy  |          |           | &#10003;      |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Legacy  | &#10003; | &#10003;  |               |
|                      | operation        |         |          |           |               |
|                      | user_agent       |         |          |           |               |
| user-password-modify | src_ip           | Default |          | &#10003;  |               |
|                      | os               | Default |          |           | &#10003;      |
|                      | additional_info  | Default |          |           | &#10003;      |
|                      | dest_ip          | Default |          | &#10003;  |               |
|                      | domain           | Default |          |           | &#10003;      |
|                      | dest_host        | Default |          | &#10003;  |               |
|                      | domain_user_name |         |          |           |               |
|                      | user             | Default |          | &#10003;  |               |
|                      | operation        | Default |          |           | &#10003;      |
|                      | user_agent       | Default |          |           | &#10003;      |
| user-switch          | process_id       |         |          |           |               |
|                      | process_name     |         |          |           |               |
|                      | service_name     |         |          |           |               |
|                      | process_dir      |         |          |           |               |
|                      | process_path     |         |          |           |               |

