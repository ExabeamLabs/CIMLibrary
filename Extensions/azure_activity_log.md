azure activity log
==================

Expression
----------

product = "azure activity log"

Fields
------

| Field               | Core | Detection | Informational |
| ------------------- | ---- | --------- | ------------- |
| tenant_id           |      |           | &#10003;      |
| resource            |      | &#10003;  |               |
| service_name        |      | &#10003;  |               |
| resource_type       |      |           | &#10003;      |
| domain_user_name    |      |           |               |
| operation_first     |      |           | &#10003;      |
| event_category      |      |           | &#10003;      |
| src_ip              |      | &#10003;  |               |
| operation_name      |      |           | &#10003;      |
| result              |      | &#10003;  |               |
| subscription_id     |      |           | &#10003;      |
| resource_group      |      |           | &#10003;      |
| domain              |      |           | &#10003;      |
| resource_path       |      |           | &#10003;      |
| correlation_id      |      |           | &#10003;      |
| result_code         |      |           | &#10003;      |
| operation_last      |      |           | &#10003;      |
| resource_name       |      |           | &#10003;      |
| authorization_scope |      |           | &#10003;      |
| user                |      | &#10003;  |               |
| operation           |      | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field                | Status  | Core | Detection | Informational |
| ---------------------- | -------------------- | ------- | ---- | --------- | ------------- |
| bucket-write           |                      |         |      |           |               |
| disk-read              |                      |         |      |           |               |
| disk-write             | src_resource         | Default |      |           | &#10003;      |
|                        | disk_state           | Default |      |           | &#10003;      |
|                        | os_type              | Default |      |           | &#10003;      |
|                        | dest_host            | Default |      | &#10003;  |               |
|                        | disk_size            | Default |      |           | &#10003;      |
|                        | resource_name        | Default |      |           | &#10003;      |
|                        | region               | Default |      |           | &#10003;      |
|                        | src_resource_type    | Default |      |           | &#10003;      |
| endpoint-command       |                      |         |      |           |               |
| endpoint-key-write     | key_name             | Default |      |           | &#10003;      |
| endpoint-write         | image_name           | Default |      |           | &#10003;      |
|                        | instance_id          | Default |      |           | &#10003;      |
|                        | interface_id         | Default |      |           | &#10003;      |
|                        | image_publisher      | Default |      |           | &#10003;      |
|                        | os_admin             | Default |      |           | &#10003;      |
|                        | image_release        | Default |      |           | &#10003;      |
|                        | os_type              | Default |      |           | &#10003;      |
|                        | vm_size              | Default |      |           | &#10003;      |
|                        | resource_name        | Default |      |           | &#10003;      |
|                        | region               | Default |      |           | &#10003;      |
|                        | image_version        | Default |      |           | &#10003;      |
|                        | src_resource_type    | Default |      |           | &#10003;      |
| image-write            | src_resource         | Default |      |           | &#10003;      |
|                        | os_type              | Default |      |           | &#10003;      |
|                        | resource_name        | Default |      |           | &#10003;      |
|                        | region               | Default |      |           | &#10003;      |
| role-write             | role                 | Default |      |           | &#10003;      |
|                        | assignble_scope      | Default |      |           | &#10003;      |
|                        | allowed_data_actions | Default |      |           | &#10003;      |
|                        | role_definition      | Default |      |           | &#10003;      |
|                        | description          | Default |      |           | &#10003;      |
|                        | allowed_permissions  | Default |      |           | &#10003;      |
|                        | denied_data_actions  | Default |      |           | &#10003;      |
| snapshot-read          |                      |         |      |           |               |
| snapshot-write         | src_resource         | Default |      |           | &#10003;      |
|                        | os_type              | Default |      |           | &#10003;      |
|                        | region               | Default |      |           | &#10003;      |
|                        | src_resource_type    | Default |      |           | &#10003;      |
| user-permission-modify | assignment_id        |         |      |           |               |
|                        | role_definition_id   |         |      |           |               |
|                        | principal_type       |         |      |           |               |
|                        | principal_id         |         |      |           |               |

