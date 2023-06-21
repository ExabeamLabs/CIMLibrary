Fields Mapping
==============

### Old Event: gcp-bucket-create
### New-Scale Activity Type: bucket-create:success

This table maps Old Event fields to the New-Scale fields that correspond to the Common Information Model.

| Old Fields                                          | New-Scale Fields            |
| --------------------------------------------------- | --------------------------- |
| bucket                                              | bucket_name                 |
| target_domain                                       | dest_domain                 |
| device                                              | device_name                 |
| user_email                                          | email_address               |
| log_type                                            | event_category              |
| user_firstname                                      | first_name                  |
| user_fullname                                       | full_name                   |
| sha256_at                                           | hash_sha256_at              |
| asset_id                                            | host_id                     |
| user_lastname                                       | last_name                   |
| source                                              | legacy_product              |
| activity_details                                    | operation_details           |
| activity_type                                       | operation_type              |
| parent_sha256hash                                   | parent_hash_sha256          |
| command_line                                        | process_command_line        |
| reason                                              | result_reason               |
| selected_sha256                                     | selected_hash_sha256        |
| service                                             | service_name                |
| sender                                              | src_email_address           |
| bytes, bytes_num, bytes_size, file_size             | bytes                       |
| tgt_user, target_user                               | dest_user                   |
| user_sid, target_user_sid                           | dest_user_sid               |
| directory, file_dir, file_parent, f_parent          | file_dir                    |
| operation, activity                                 | operation                   |
| parent_process_cmd, parent_command_line, parent_cmd | parent_process_command_line |
| parent_directory, parent_process_directory          | parent_process_dir          |
| process_id, pid                                     | process_id                  |
| process_path, process, path                         | process_path                |
| result, outcome                                     | result                      |
| rule, rule_name                                     | rule                        |
| src_domain, caller_domain                           | src_domain                  |
| src_user, caller_user                               | src_user                    |