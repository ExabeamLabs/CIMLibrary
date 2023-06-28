Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: aws-identity-list
### New-Scale Activity Type: user-list:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                                                | New-Scale Fields            |
| --------------------------------------------------------- | --------------------------- |
| bucket                                                    | bucket_name                 |
| target_domain                                             | dest_domain                 |
| device                                                    | device_name                 |
| user_email                                                | email_address               |
| log_type                                                  | event_category              |
| user_firstname                                            | first_name                  |
| user_fullname                                             | full_name                   |
| sha256_at                                                 | hash_sha256_at              |
| asset_id                                                  | host_id                     |
| user_lastname                                             | last_name                   |
| source                                                    | legacy_product              |
| activity_type                                             | operation_type              |
| parent_sha256hash                                         | parent_hash_sha256          |
| command_line                                              | process_command_line        |
| reason                                                    | result_reason               |
| selected_sha256                                           | selected_hash_sha256        |
| service                                                   | service_name                |
| sender                                                    | src_email_address           |
| bytes,<br>bytes_num,<br>bytes_size,<br>file_size          | bytes                       |
| tgt_user,<br>target_user                                  | dest_user                   |
| user_sid,<br>target_user_sid                              | dest_user_sid               |
| directory,<br>file_dir,<br>file_parent,<br>f_parent       | file_dir                    |
| operation,<br>activity                                    | operation                   |
| parent_process_cmd,<br>parent_command_line,<br>parent_cmd | parent_process_command_line |
| parent_directory,<br>parent_process_directory             | parent_process_dir          |
| process_id,<br>pid                                        | process_id                  |
| process_path,<br>process,<br>path                         | process_path                |
| result,<br>outcome                                        | result                      |
| rule,<br>rule_name                                        | rule                        |