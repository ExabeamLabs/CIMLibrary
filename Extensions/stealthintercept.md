stealthintercept
================

Expression
----------

product = "stealthintercept"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| src_ip           |      | &#10003;  |               |
| dest_ip          |      | &#10003;  |               |
| domain           |      | &#10003;  |               |
| domain_user_name |      |           |               |
| src_host         |      | &#10003;  |               |
| user             |      | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field         | Status  | Core | Detection | Informational |
| ---------------------- | ------------- | ------- | ---- | --------- | ------------- |
| ds_object-modify       | old_attribute | Default |      |           | &#10003;      |
|                        | new_attribute | Default |      |           | &#10003;      |
| endpoint-login         | auth_method   | Default |      |           | &#10003;      |
|                        | ds_object_out | Default |      |           | &#10003;      |
| file-permission-modify | access        | Legacy  |      | &#10003;  |               |
|                        | process_name  | Legacy  |      |           | &#10003;      |
| file-read              | access        | Legacy  |      | &#10003;  |               |
|                        | process_name  | Legacy  |      |           | &#10003;      |
| file-write             | access        | Legacy  |      | &#10003;  |               |
|                        | process_name  | Legacy  |      |           | &#10003;      |
| group-member-add       |               |         |      |           |               |
| group-member-remove    |               |         |      |           |               |
| user-disable           |               |         |      |           |               |
| user-enable            |               |         |      |           |               |

