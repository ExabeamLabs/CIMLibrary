Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: azure-keyvault-read
### New-Scale Activity Type: key-read:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                                                | New-Scale Fields            |
| --------------------------------------------------------- | --------------------------- |
| bucket                                                    | bucket_name                 |
| target_domain                                             | dest_domain                 |
| target_user_sid                                           | dest_user_sid               |
| device                                                    | device_name                 |
| user_email                                                | email_address               |
| log_type                                                  | event_category              |
| user_firstname                                            | first_name                  |
| user_fullname                                             | full_name                   |
| sha256_at                                                 | hash_sha256_at              |
| asset_id                                                  | host_id                     |
| user_lastname                                             | last_name                   |
| source                                                    | legacy_product              |
| m_collector_name                                          | m_collector_name            |
| m_collector_type                                          | m_collector_type            |
| m_forwarder                                               | m_forwarder                 |
| m_hostname                                                | m_hostname                  |
| m_origin_collector_name                                   | m_origin_collector_name     |
| m_origin_collector_type                                   | m_origin_collector_type     |
| m_origin_hostname                                         | m_origin_hostname           |
| m_siteid                                                  | m_siteid                    |
| m_sitename                                                | m_sitename                  |
| activity_type                                             | operation_type              |
| parent_sha256hash                                         | parent_hash_sha256          |
| command_line                                              | process_command_line        |
| reason                                                    | result_reason               |
| selected_sha256                                           | selected_hash_sha256        |
| service                                                   | service_name                |
| sender                                                    | src_email_address           |
| full_url                                                  | url                         |
| bytes,<br>bytes_num,<br>bytes_size,<br>file_size          | bytes                       |
| tgt_user,<br>target_user                                  | dest_user                   |
| directory,<br>file_dir,<br>file_parent,<br>f_parent       | file_dir                    |
| operation,<br>activity                                    | operation                   |
| parent_process_cmd,<br>parent_command_line,<br>parent_cmd | parent_process_command_line |
| parent_directory,<br>parent_process_directory             | parent_process_dir          |
| process_id,<br>pid                                        | process_id                  |
| process_path,<br>process,<br>path                         | process_path                |
| result,<br>outcome                                        | result                      |
| rule,<br>rule_name                                        | rule                        |