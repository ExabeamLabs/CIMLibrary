aws cloudtrail
==============

Expression
----------

product = "aws cloudtrail"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| aws_email_address  |      |           | &#10003;      |
| service_name       |      | &#10003;  |               |
| aws_account        |      | &#10003;  |               |
| vpc                |      |           | &#10003;      |
| mfa                |      | &#10003;  |               |
| fallback_user_name |      |           |               |
| domain_user_name   |      |           |               |
| user_arn           |      |           | &#10003;      |
| src_host           |      |           | &#10003;      |
| aws_user           |      |           | &#10003;      |
| event_category     |      | &#10003;  |               |
| principal_id       |      |           | &#10003;      |
| src_ip             |      | &#10003;  |               |
| user_type          |      | &#10003;  |               |
| readonly           |      | &#10003;  |               |
| domain             |      |           | &#10003;      |
| region             |      | &#10003;  |               |
| operation          |      | &#10003;  |               |
| user               |      | &#10003;  |               |
| user_agent         |      | &#10003;  |               |
| policy             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type             | Field                   | Status  | Core     | Detection | Informational |
| ------------------------- | ----------------------- | ------- | -------- | --------- | ------------- |
| app-login                 | result                  | Default |          |           | &#10003;      |
|                           | mobile_version          | Default |          |           | &#10003;      |
|                           | mfa                     | Default |          |           | &#10003;      |
|                           | url                     | Default |          |           | &#10003;      |
| bucket-accessblock-modify | block_public_policy     | Default |          |           | &#10003;      |
|                           | block_public_acls       | Default |          |           | &#10003;      |
|                           | bucket_arn              | Default |          |           | &#10003;      |
|                           | ignore_public_acls      | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
|                           | restrict_public_buckets | Default |          |           | &#10003;      |
| bucket-create             | bucket_host             | Default |          |           | &#10003;      |
| bucket-list               |                         |         |          |           |               |
| bucket-permission-modify  | acl_content             | Default |          |           | &#10003;      |
|                           | allowed_ids             | Default |          |           | &#10003;      |
|                           | allowed_user_types      | Default |          |           | &#10003;      |
|                           | bucket_arn              | Default |          |           | &#10003;      |
|                           | allowed_uris            | Default |          |           | &#10003;      |
|                           | owner_id                | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
|                           | allowed_permissions     | Default |          |           | &#10003;      |
| bucket-permission-read    | acl_content             | Default |          |           | &#10003;      |
|                           | bucket_arn              | Default |          |           | &#10003;      |
|                           | owner_id                | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
| bucket-policy-modify      | allowed_users           | Default |          |           | &#10003;      |
|                           | bucket_arn              | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
|                           | denied_permissions      | Default |          |           | &#10003;      |
|                           | denied_users            | Default |          |           | &#10003;      |
|                           | allowed_permissions     | Default |          |           | &#10003;      |
|                           | allowed_resources       | Default |          |           | &#10003;      |
|                           | denied_resources        | Default |          |           | &#10003;      |
| bucket-policy-read        | bucket_arn              | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
| bucket-property-read      | bucket_arn              | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
| disk-attach               | instance_id             | Default |          |           | &#10003;      |
|                           | volume_device           | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| disk-create               | volume_type             | Default |          |           | &#10003;      |
|                           | src_resource            | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
|                           | volume_size             | Default |          |           | &#10003;      |
|                           | volume_zone             | Default |          |           | &#10003;      |
| disk-list                 |                         |         |          |           |               |
| disk-modify               | old_size                | Default |          |           | &#10003;      |
|                           | old_multiattach         | Default |          |           | &#10003;      |
|                           | volume_type             | Default |          |           | &#10003;      |
|                           | new_size                | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
|                           | new_multiattach         | Default |          |           | &#10003;      |
| endpoint-command          | document_name           | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
|                           | playbook_files          | Default |          |           | &#10003;      |
| endpoint-create           | key_name                | Default |          |           | &#10003;      |
|                           | new_host                | Default |          |           | &#10003;      |
|                           | availabilty_zone        | Default |          |           | &#10003;      |
|                           | src_resource            | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
|                           | security_group          | Default |          |           | &#10003;      |
|                           | instance_type           | Default |          |           | &#10003;      |
|                           | new_ip                  | Default |          |           | &#10003;      |
|                           | instance_profile_arn    | Default |          |           | &#10003;      |
| endpoint-key-create       | key_name                | Default |          |           | &#10003;      |
|                           | key_type                | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| endpoint-list             |                         |         |          |           |               |
| endpoint-login            | resource_id             | Default |          |           | &#10003;      |
|                           | dest_user               | Default |          | &#10003;  |               |
| endpoint-modify           | userdata                |         |          | &#10003;  |               |
|                           | modified_keys           |         |          | &#10003;  |               |
|                           | added_keys              |         |          | &#10003;  |               |
|                           | resource_id             |         |          |           | &#10003;      |
| endpoint-screenshot       | resource_id             | Default |          |           | &#10003;      |
| file-copy                 | bucket_arn              | Default |          |           | &#10003;      |
|                           | bytes_out               | Default |          |           | &#10003;      |
|                           | src_bucket_arn          | Default |          |           | &#10003;      |
|                           | bytes_in                | Default |          |           | &#10003;      |
|                           | bucket_name             | Default |          |           | &#10003;      |
|                           | file_arn                | Default |          |           | &#10003;      |
|                           | bucket_host             | Default |          |           | &#10003;      |
|                           | src_file_arn            | Default |          |           | &#10003;      |
| file-list                 |                         |         |          |           |               |
| file-permission-modify    | acl_content             |         |          | &#10003;  |               |
|                           | allowed_ids             |         |          |           |               |
|                           | allowed_user_types      |         |          |           |               |
|                           | bucket_arn              |         |          |           |               |
|                           | bytes_out               |         |          |           |               |
|                           | allowed_uris            |         |          |           |               |
|                           | owner_id                |         |          |           |               |
|                           | bucket_name             |         |          | &#10003;  |               |
|                           | file_arn                |         |          |           |               |
|                           | bucket_host             |         |          |           |               |
|                           | allowed_permissions     |         |          |           |               |
| file-read                 | bucket_arn              |         |          |           | &#10003;      |
|                           | bytes_out               |         |          |           | &#10003;      |
|                           | bucket_name             |         |          | &#10003;  |               |
|                           | file_arn                |         |          |           | &#10003;      |
|                           | bucket_host             |         |          |           | &#10003;      |
| file-write                | bucket_arn              |         |          |           | &#10003;      |
|                           | bytes_in                |         |          |           | &#10003;      |
|                           | bucket_name             |         |          | &#10003;  |               |
|                           | file_arn                |         |          |           | &#10003;      |
|                           | bucket_host             |         |          |           | &#10003;      |
| function-create           | hash_sha256             | Default |          |           | &#10003;      |
|                           | code_size               | Default |          |           | &#10003;      |
|                           | function_name           | Default |          |           | &#10003;      |
|                           | function_arn            | Default |          |           | &#10003;      |
|                           | function_runtime        | Default |          |           | &#10003;      |
|                           | function_role           | Default |          |           | &#10003;      |
| function-modify           | hash_sha256             | Default |          |           | &#10003;      |
|                           | code_size               | Default |          |           | &#10003;      |
|                           | function_name           | Default |          |           | &#10003;      |
|                           | function_arn            | Default |          |           | &#10003;      |
|                           | function_runtime        | Default |          |           | &#10003;      |
|                           | function_role           | Default |          |           | &#10003;      |
| group-create              | group_id                |         |          |           | &#10003;      |
|                           | group_arn               |         |          |           | &#10003;      |
| group-list                |                         |         |          |           |               |
| group-member-add          |                         |         |          |           |               |
| image-create              | src_resource            | Default |          |           | &#10003;      |
|                           | image_publisher         |         |          | &#10003;  |               |
|                           | description             | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| image-list                |                         |         |          |           |               |
| image-modify              | removed_users           | Default |          |           | &#10003;      |
|                           | added_users             | Default |          |           | &#10003;      |
|                           | resource                | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| policy-attach             | policy_arn              | Default |          |           | &#10003;      |
|                           | dest_role               | Default |          |           | &#10003;      |
|                           | dest_group              | Default |          |           | &#10003;      |
|                           | dest_user               | Default |          | &#10003;  |               |
| policy-create             | policy_arn              | Default |          |           | &#10003;      |
|                           | policy_content          | Default |          |           | &#10003;      |
|                           | dest_role               | Default |          |           | &#10003;      |
|                           | policy_id               | Default |          |           | &#10003;      |
|                           | dest_group              | Default |          |           | &#10003;      |
|                           | set_as_defualt          | Default |          |           | &#10003;      |
|                           | dest_user               | Default |          | &#10003;  |               |
|                           | denied_permissions      | Default |          |           | &#10003;      |
|                           | allowed_permissions     | Default |          |           | &#10003;      |
|                           | allowed_resources       | Default |          |           | &#10003;      |
|                           | policy_version_id       | Default |          |           | &#10003;      |
|                           | denied_resources        | Default |          |           | &#10003;      |
| policy-list               | dest_role               | Default |          |           | &#10003;      |
|                           | dest_group              | Default |          |           | &#10003;      |
|                           | dest_user               | Default |          | &#10003;  |               |
| role-assume               | session_name            | Default |          |           | &#10003;      |
|                           | transistive_tags        | Default |          |           | &#10003;      |
|                           | role_arn                | Default |          |           | &#10003;      |
|                           | session_arn             | Default |          |           | &#10003;      |
|                           | src_role                | Default |          |           | &#10003;      |
|                           | session_expiration      | Default |          |           | &#10003;      |
|                           | url                     | Default |          |           | &#10003;      |
|                           | session_tag             | Default |          |           | &#10003;      |
| role-create               | policy_content          | Default |          |           | &#10003;      |
|                           | allowed_users           | Default |          |           | &#10003;      |
|                           | role_arn                | Default |          |           | &#10003;      |
|                           | denied_users            | Default |          |           | &#10003;      |
| role-list                 |                         |         |          |           |               |
| role-policy-modify        | policy_content          | Default |          |           | &#10003;      |
|                           | dest_role               | Default |          |           | &#10003;      |
|                           | allowed_users           | Default |          |           | &#10003;      |
|                           | denied_users            | Default |          |           | &#10003;      |
| snapshot-create           | src_resource            | Default |          |           | &#10003;      |
|                           | owner_id                | Default |          |           | &#10003;      |
|                           | description             | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| snapshot-list             |                         |         |          |           |               |
| snapshot-modify           | removed_users           | Default |          |           | &#10003;      |
|                           | added_users             | Default |          |           | &#10003;      |
|                           | resource_id             | Default |          |           | &#10003;      |
| user-create               | dest_user_arn           |         |          |           | &#10003;      |
|                           | dest_user_id            |         | &#10003; |           |               |
| user-key-create           | key_id                  | Default |          |           | &#10003;      |
|                           | dest_user_id            | Default |          |           | &#10003;      |
|                           | key_status              | Default |          |           | &#10003;      |
| user-list                 |                         |         |          |           |               |
| user-modify               |                         |         |          |           |               |
| user-password-read        | resource_id             |         |          |           | &#10003;      |

