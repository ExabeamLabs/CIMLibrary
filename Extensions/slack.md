slack
=====

Expression
----------

product = "slack"

Fields
------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| user_id    |      |           | &#10003;      |
| file_type  |      |           | &#10003;      |
| dest_ip    |      |           | &#10003;      |
| dest_host  |      |           | &#10003;      |
| user_agent |      |           | &#10003;      |

Activity Types
--------------

| Activity Type          | Field            | Status  | Core     | Detection | Informational |
| ---------------------- | ---------------- | ------- | -------- | --------- | ------------- |
| app-login              | file_ext         | Default |          |           | &#10003;      |
|                        | file_name        | Default |          |           | &#10003;      |
| app-logout             | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| channel-create         | operation        | Default |          |           | &#10003;      |
| channel-delete         | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| channel-member-join    | app              | Default |          |           | &#10003;      |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| channel-member-leave   | app              | Default |          |           | &#10003;      |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| channel-modify         | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| file-download          | domain           |         |          |           |               |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
| file-share             | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
| file-upload            | domain           |         |          |           |               |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
| group-member-add       | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| group-member-remove    | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| group-role-assign      | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| group-role-modify      | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| group-role-revoke      | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| user-create            | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| user-disable           | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | operation        |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
|                        | object           |         |          |           |               |
| user-enable            | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; | &#10003;  |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| user-modify            | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; |           |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| user-permission-modify | src_ip           |         |          |           |               |
|                        | app              |         |          |           |               |
|                        | domain           | Legacy  |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Legacy  | &#10003; |           |               |
|                        | operation        |         |          |           |               |
|                        | object           |         |          |           |               |
| user-role-assign       | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| user-role-modify       | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| user-role-revoke       | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| workspace-create       | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| workspace-delete       | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |
| workspace-member-add   | src_ip           | Default |          | &#10003;  |               |
|                        | app              | Default |          |           | &#10003;      |
|                        | domain           | Default |          |           | &#10003;      |
|                        | domain_user_name |         |          |           |               |
|                        | user             | Default |          | &#10003;  |               |
|                        | operation        | Default |          |           | &#10003;      |
|                        | object           | Default |          |           | &#10003;      |

