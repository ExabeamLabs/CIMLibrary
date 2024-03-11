quest change auditor for active directory
=========================================

Expression
----------

product = "quest change auditor for active directory"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type        | Field           | Status  | Core     | Detection | Informational |
| -------------------- | --------------- | ------- | -------- | --------- | ------------- |
| ds_object-activity   | host_ip         | Default |          |           | &#10003;      |
|                      | old_attribute   | Default |          |           | &#10003;      |
|                      | operation_type  | Default |          |           | &#10003;      |
|                      | new_attribute   | Default |          |           | &#10003;      |
|                      | src_host        | Default |          | &#10003;  |               |
|                      | object_ou       | Default |          |           | &#10003;      |
|                      | src_ip          | Default |          | &#10003;  |               |
|                      | dest_ip         | Default |          | &#10003;  |               |
|                      | domain          | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |
|                      | attribute       | Default |          |           | &#10003;      |
|                      | object_dn       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
|                      | object_class    | Default |          |           | &#10003;      |
|                      | dest_port       | Default |          |           | &#10003;      |
|                      | object          | Default |          |           | &#10003;      |
| endpoint-login       | src_ip          | Default |          | &#10003;  |               |
|                      | user_id         | Default |          |           | &#10003;      |
|                      | dest_ip         | Default |          | &#10003;  |               |
|                      | event_name      | Default |          |           | &#10003;      |
| file-delete          | src_ip          |         |          | &#10003;  |               |
|                      | access          | Legacy  |          | &#10003;  |               |
|                      | user_id         |         |          |           | &#10003;      |
|                      | additional_info |         |          |           | &#10003;      |
|                      | alert_severity  |         |          |           | &#10003;      |
|                      | domain          |         |          |           | &#10003;      |
|                      | src_host        | Legacy  |          | &#10003;  |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | operation       |         |          |           | &#10003;      |
| file-read            | src_ip          |         |          | &#10003;  |               |
|                      | access          | Legacy  |          | &#10003;  |               |
|                      | user_id         |         |          |           | &#10003;      |
|                      | additional_info |         |          |           | &#10003;      |
|                      | alert_severity  |         |          |           | &#10003;      |
|                      | domain          |         |          |           | &#10003;      |
|                      | src_host        | Legacy  |          | &#10003;  |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | operation       |         |          |           | &#10003;      |
| file-write           | src_ip          |         |          | &#10003;  |               |
|                      | access          | Legacy  |          | &#10003;  |               |
|                      | user_id         |         |          |           | &#10003;      |
|                      | additional_info |         |          |           | &#10003;      |
|                      | alert_severity  |         |          |           | &#10003;      |
|                      | domain          |         |          |           | &#10003;      |
|                      | src_host        |         |          | &#10003;  |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | operation       |         |          |           | &#10003;      |
| group-member-add     | src_ip          |         |          |           |               |
|                      | user_id         |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | event_name      |         |          |           |               |
|                      | dest_user_id    |         |          |           |               |
| group-member-remove  | src_ip          |         |          |           |               |
|                      | user_id         |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | event_name      |         |          |           |               |
|                      | dest_user_id    |         |          |           |               |
| user-lock            | src_ip          |         |          |           |               |
|                      | dest_user_ou    |         |          |           |               |
|                      | user_id         |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | event_name      |         |          |           |               |
| user-password-modify | src_ip          | Default |          | &#10003;  |               |
|                      | user_id         | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |

