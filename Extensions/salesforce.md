salesforce
==========

Expression
----------

product = "salesforce"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| domain             |          | &#10003;  |               |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field           | Status  | Core     | Detection | Informational |
| ---------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity           | src_ip          | Default |          | &#10003;  |               |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | bytes           | Default |          |           | &#10003;      |
|                        | dest_user       | Default |          | &#10003;  |               |
|                        | old_value       | Default |          |           | &#10003;      |
|                        | new_value       | Default |          |           | &#10003;      |
|                        | user_agent      | Default |          |           | &#10003;      |
|                        | object          | Default |          |           | &#10003;      |
| app-login              | src_ip          | Default |          | &#10003;  |               |
|                        | os              | Default |          |           | &#10003;      |
|                        | browser         | Default |          |           | &#10003;      |
|                        | dest_host       | Default |          | &#10003;  |               |
|                        | user_agent      | Default |          |           | &#10003;      |
| app-logout             | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| app-notification       | resource        | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
|                        | object          | Default |          |           | &#10003;      |
| configuration-modify   | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |
|                        | object          |         |          |           |               |
| file-delete            | additional_info |         |          |           |               |
|                        | dest_user       |         |          |           |               |
|                        | operation       |         |          |           |               |
| file-property-modify   | old_value       | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
|                        | new_value       | Default |          |           | &#10003;      |
| group-member-add       | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |
| group-member-move      | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| role-create            | role_type       | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| role-delete            | role_type       | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| role-modify            | role_type       | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| role-permission-modify | role_type       | Default |          |           | &#10003;      |
|                        | additional_info | Default |          |           | &#10003;      |
|                        | permission      | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| user-create            | additional_info |         |          |           |               |
| user-disable           | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |
| user-enable            | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |
| user-lock              | src_ip          |         |          |           |               |
|                        | additional_info |         |          |           |               |
|                        | dest_host       | Legacy  |          |           | &#10003;      |
|                        | src_host        | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-modify            | additional_info |         |          |           |               |
|                        | old_value       |         |          |           |               |
|                        | operation       |         |          |           |               |
|                        | new_value       |         |          |           |               |
|                        | object          |         |          |           |               |
| user-password-expire   | additional_info | Default |          |           | &#10003;      |
|                        | resource        | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
|                        | object          | Default |          |           | &#10003;      |
| user-password-modify   | operation       | Default |          |           | &#10003;      |
| user-password-reset    | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |
| user-role-assign       | additional_info | Default |          |           | &#10003;      |
|                        | resource        | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| user-unlock            | additional_info |         |          |           |               |
|                        | operation       |         |          |           |               |

