gcp cloud audit
===============

Expression
----------

product = "gcp cloud audit"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| service_name       |      | &#10003;  |               |
| resource_dir       |      |           | &#10003;      |
| resource_type      |      |           | &#10003;      |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| event_category     |      |           | &#10003;      |
| operation_first    |      |           | &#10003;      |
| src_ip             |      | &#10003;  |               |
| project_id         |      |           | &#10003;      |
| zone               |      |           | &#10003;      |
| domain             |      |           | &#10003;      |
| resource_path      |      | &#10003;  |               |
| result_code        |      |           | &#10003;      |
| resource_name      |      |           | &#10003;      |
| region             |      | &#10003;  |               |
| operation_last     |      |           | &#10003;      |
| user               |      | &#10003;  |               |
| operation          |      | &#10003;  |               |
| user_agent         |      | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field                  | Status  | Core | Detection | Informational |
| ---------------------- | ---------------------- | ------- | ---- | --------- | ------------- |
| bucket-create          |                        |         |      |           |               |
| bucket-list            |                        |         |      |           |               |
| disk-attach            | device_name            | Default |      |           | &#10003;      |
|                        | disk_mode              | Default |      |           | &#10003;      |
|                        | src_resource           | Default |      |           | &#10003;      |
| disk-create            | src_resource           | Default |      |           | &#10003;      |
| disk-list              |                        |         |      |           |               |
| endpoint-create        | machine_type           | Default |      |           | &#10003;      |
|                        | src_resource           | Default |      |           | &#10003;      |
|                        | subnetwork             | Default |      |           | &#10003;      |
|                        | linked_service_account | Default |      |           | &#10003;      |
| endpoint-list          |                        |         |      |           |               |
| endpoint-modify        | machine_type           |         |      |           | &#10003;      |
|                        | modified_keys          |         |      | &#10003;  |               |
|                        | added_keys             |         |      | &#10003;  |               |
| endpoint-screenshot    |                        |         |      |           |               |
| file-list              |                        |         |      |           |               |
| file-permission-modify | acl_content            |         |      | &#10003;  |               |
|                        | added_role_name        |         |      |           | &#10003;      |
|                        | added_member           |         |      |           | &#10003;      |
|                        | bucket_name            |         |      | &#10003;  |               |
|                        | added_member_type      |         |      |           | &#10003;      |
|                        | policy_bindings        |         |      | &#10003;  |               |
|                        | policy_delta           |         |      | &#10003;  |               |
|                        | removed_role           |         |      |           | &#10003;      |
|                        | added_role             |         |      |           | &#10003;      |
|                        | removed_role_name      |         |      |           | &#10003;      |
|                        | removed_member         |         |      |           | &#10003;      |
|                        | removed_member_type    |         |      |           | &#10003;      |
| file-read              |                        |         |      |           |               |
| file-write             |                        |         |      |           |               |
| function-create        |                        |         |      |           |               |
| image-create           | src_resource           | Default |      |           | &#10003;      |
|                        | image_publisher        |         |      | &#10003;  |               |
| policy-modify          | added_role_name        | Default |      |           | &#10003;      |
|                        | added_member           | Default |      |           | &#10003;      |
|                        | added_member_type      | Default |      |           | &#10003;      |
|                        | policy_bindings        | Default |      |           | &#10003;      |
|                        | policy_delta           | Default |      |           | &#10003;      |
|                        | removed_role           | Default |      |           | &#10003;      |
|                        | added_role             | Default |      |           | &#10003;      |
|                        | removed_role_name      | Default |      |           | &#10003;      |
|                        | removed_member         | Default |      |           | &#10003;      |
|                        | removed_member_type    | Default |      |           | &#10003;      |
|                        | policy                 |         |      |           | &#10003;      |
| role-create            | role_permissions       | Default |      |           | &#10003;      |
|                        | removed_permissions    | Default |      |           | &#10003;      |
|                        | added_permissions      | Default |      |           | &#10003;      |
| role-list              |                        |         |      |           |               |
| role-modify            | role_permissions       | Default |      |           | &#10003;      |
|                        | removed_permissions    | Default |      |           | &#10003;      |
|                        | added_permissions      | Default |      |           | &#10003;      |
| snapshot-create        | src_resource           | Default |      |           | &#10003;      |
| snapshot-list          |                        |         |      |           |               |
| user-create            |                        |         |      |           |               |
| user-key-create        |                        |         |      |           |               |

