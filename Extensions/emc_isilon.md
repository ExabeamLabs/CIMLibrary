emc isilon
==========

Expression
----------

product = "emc isilon"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field         | Status  | Core | Detection | Informational |
| ---------------------- | ------------- | ------- | ---- | --------- | ------------- |
| endpoint-login         | src_ip        | Default |      | &#10003;  |               |
|                        | zone_id       | Default |      |           | &#10003;      |
|                        | protocol      | Default |      |           | &#10003;      |
|                        | user_id       | Default |      |           | &#10003;      |
|                        | event_name    | Default |      |           | &#10003;      |
|                        | src_host      | Default |      | &#10003;  |               |
| file-delete            | src_ip        |         |      |           |               |
|                        | inode         |         |      |           |               |
|                        | zone_id       |         |      |           |               |
|                        | server_name   |         |      |           |               |
|                        | desire_access |         |      |           |               |
|                        | protocol      |         |      |           |               |
|                        | access        | Legacy  |      | &#10003;  |               |
|                        | user_id       |         |      |           |               |
|                        | file_type     | Legacy  |      |           | &#10003;      |
|                        | create_result |         |      |           |               |
| file-permission-modify | src_ip        |         |      |           |               |
|                        | inode         |         |      |           |               |
|                        | zone_id       |         |      |           |               |
|                        | server_name   |         |      |           |               |
|                        | desire_access |         |      |           |               |
|                        | protocol      |         |      |           |               |
|                        | access        | Legacy  |      | &#10003;  |               |
|                        | user_id       |         |      |           |               |
|                        | file_type     | Legacy  |      |           | &#10003;      |
|                        | create_result |         |      |           |               |
| file-read              | src_ip        |         |      |           |               |
|                        | inode         |         |      |           |               |
|                        | zone_id       |         |      |           |               |
|                        | server_name   |         |      |           |               |
|                        | desire_access |         |      |           |               |
|                        | protocol      |         |      |           |               |
|                        | access        | Legacy  |      | &#10003;  |               |
|                        | user_id       |         |      |           |               |
|                        | file_type     | Legacy  |      |           | &#10003;      |
|                        | create_result |         |      |           |               |
| file-write             | src_ip        |         |      |           |               |
|                        | inode         |         |      |           |               |
|                        | zone_id       |         |      |           |               |
|                        | server_name   |         |      |           |               |
|                        | desire_access |         |      |           |               |
|                        | protocol      |         |      |           |               |
|                        | access        | Legacy  |      | &#10003;  |               |
|                        | user_id       |         |      |           |               |
|                        | file_type     | Legacy  |      |           | &#10003;      |
|                        | create_result |         |      |           |               |

