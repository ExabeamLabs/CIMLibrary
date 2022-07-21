moveit transfer
===============

Expression
----------

product = "moveit transfer"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      | &#10003;  |               |
| operation |      |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field           | Status  | Core | Detection | Informational |
| -------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity         | file_ext        | Default |      |           | &#10003;      |
|                      | user_id         | Default |      |           | &#10003;      |
|                      | additional_info | Default |      |           | &#10003;      |
|                      | file_name       | Default |      |           | &#10003;      |
|                      | dest_ip         | Default |      | &#10003;  |               |
|                      | file_id         | Default |      |           | &#10003;      |
|                      | file_dir        | Default |      |           | &#10003;      |
|                      | dest_host       | Default |      | &#10003;  |               |
|                      | user_agent      | Default |      |           | &#10003;      |
| app-authentication   |                 |         |      |           |               |
| app-login            | src_ip          | Default |      | &#10003;  |               |
|                      | user_id         | Default |      |           | &#10003;      |
|                      | src_host        | Default |      | &#10003;  |               |
|                      | user_agent      | Default |      |           | &#10003;      |
| file-delete          | bytes           |         |      |           |               |
|                      | file_id         |         |      |           |               |
| file-download        | bytes           | Legacy  |      | &#10003;  |               |
|                      | file_id         |         |      |           |               |
| file-read            | src_ip          |         |      |           |               |
|                      | user_id         |         |      |           |               |
|                      | additional_info |         |      |           |               |
|                      | src_host        | Legacy  |      | &#10003;  |               |
|                      | user_agent      |         |      |           |               |
| file-upload          | bytes           |         |      |           |               |
|                      | file_id         |         |      |           |               |
| file-write           | src_ip          |         |      |           |               |
|                      | user_id         |         |      |           |               |
|                      | additional_info |         |      |           |               |
|                      | bytes           | Legacy  |      | &#10003;  |               |
|                      | file_id         |         |      |           |               |
|                      | src_host        |         |      |           |               |
|                      | user_agent      |         |      |           |               |
| group-member-add     | dest_user_id    |         |      |           |               |
| group-member-remove  | dest_user_id    |         |      |           |               |
| user-password-modify | dest_user_id    | Default |      |           | &#10003;      |

