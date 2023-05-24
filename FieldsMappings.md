 Field Mapping by Event
=======================

 This table maps old event types and fields to the coresponding activity types and fields in Common Information Model

| Old Event | Common Information Model Activity Type| Old Fields | Common Information Model Fields |
| --------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------- |
| dlp-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| rules| rule|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| threat_score, score, risk_score| original_risk_score |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| security-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| cve| cve_id|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| alert_name, alert| alert_name|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| malware_filename, malware_file_name| malware_file_name |
| &nbsp;| &nbsp;| threat_score, score, risk_score| original_risk_score |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_process_id, parent_pid| parent_process_id |
| &nbsp;| &nbsp;| policy, policy_name| policy_name |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome, action_blocked, action_success| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| rule_num, rule_count | rule_count|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| user, suser| user|
| &nbsp;| &nbsp;| user_id, uid | user_id |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| process-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_process_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_path|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| group_name, user_group | user_group_name |
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| file-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| network-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| rule_num | rule_count|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| appid, application_id| app_id|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| destination_country, dest_country| dest_country|
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, event_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| dest_country, source_country | src_country |
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| alert-iot | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| database-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_group | dest_group|
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| database_schema, schema| db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| app-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| aws-identity-loginprofile-failed| [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-screenshot-failed| [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-general-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-command-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| cloud-admin-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| group| group_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| app-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| webconference-operations-activity | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-general-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-general-activity| [app-activity:success](ActivityTypes/app-activity.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-loginprofile | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-command| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-screenshot | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| cloud-admin-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| group| group_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| authentication-failed | [app-authentication:fail](ActivityTypes/app-authentication.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| authentication-successful | [app-authentication:success](ActivityTypes/app-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| app-login | [app-authentication:success](ActivityTypes/app-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| failed-app-login| [app-login:fail](ActivityTypes/app-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| aws-login-failed| [app-login:fail](ActivityTypes/app-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| webconference-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-logout| [app-logout:fail](ActivityTypes/app-logout.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| app-logout| [app-logout:success](ActivityTypes/app-logout.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| audit-policy-change | [audit_policy-modify:success](ActivityTypes/audit_policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| policy | audit_policy_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-accessblock-failed | [bucket-accessblock-modify:fail](ActivityTypes/bucket-accessblock-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-accessblock| [bucket-accessblock-modify:success](ActivityTypes/bucket-accessblock-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-create-failed| [bucket-create:fail](ActivityTypes/bucket-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-bucket-create | [bucket-create:success](ActivityTypes/bucket-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-create | [bucket-create:success](ActivityTypes/bucket-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-list-failed | [bucket-list:fail](ActivityTypes/bucket-list.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-storage-list| [bucket-list:success](ActivityTypes/bucket-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-list| [bucket-list:success](ActivityTypes/bucket-list.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-acl-failed| [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-cors-failed| [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-policy-write| [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-acl | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-cors | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-policy-failed| [bucket-policy-modify:fail](ActivityTypes/bucket-policy-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-policy | [bucket-policy-modify:success](ActivityTypes/bucket-policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| system-info | [certificate-request:success](ActivityTypes/certificate-request.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| system-info | [certificate-validate:success](ActivityTypes/certificate-validate.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| app-activity| [configuration-mfa-enable:success](ActivityTypes/configuration-mfa-enable.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| config-change | [configuration-modify:fail](ActivityTypes/configuration-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| config-change | [configuration-modify:success](ActivityTypes/configuration-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| database-activity-failed| [database-activity:fail](ActivityTypes/database-activity.md)| accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-access | [database-activity:success](ActivityTypes/database-activity.md) | accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| schema | db_schema |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_object, database_objects| db_object |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-delete | [database-delete:success](ActivityTypes/database-delete.md) | accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| database_schema| db_schema |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-failed-login | [database-login:fail](ActivityTypes/database-login.md)| accesses | access|
| &nbsp;| &nbsp;| database_id| db_id |
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| schema | db_schema |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| source_program | src_interface |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| reason, failure_reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| database-login| [database-login:success](ActivityTypes/database-login.md) | accesses | access|
| &nbsp;| &nbsp;| database_id| db_id |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| schema, db_schema, database_schema | db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-update | [database-modify:success](ActivityTypes/database-modify.md) | accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_schema, schema| db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-query| [database-query:fail](ActivityTypes/database-query.md)| accesses | access|
| &nbsp;| &nbsp;| database_id| db_id |
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| source_program | src_interface |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_schema, schema| db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| database-query| [database-query:success](ActivityTypes/database-query.md) | accesses | access|
| &nbsp;| &nbsp;| database_id| db_id |
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| source_program | src_interface |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_schema, schema| db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| dcom-activation-failed| [dcom-activate:fail](ActivityTypes/dcom-activate.md)| accesses | access|
| &nbsp;| &nbsp;| appid| app_id|
| &nbsp;| &nbsp;| clsid| cls_id|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_sid, sid| user_sid|
| computer-logon| [dhcp-session:success](ActivityTypes/dhcp-session.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| uids | user_uids |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| aws-volume-attach-failed| [disk-attach:fail](ActivityTypes/disk-attach.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-disk-attach | [disk-attach:success](ActivityTypes/disk-attach.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-volume-attach | [disk-attach:success](ActivityTypes/disk-attach.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-volume-create-failed| [disk-create:fail](ActivityTypes/disk-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-disk-create | [disk-create:success](ActivityTypes/disk-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-volume-create | [disk-create:success](ActivityTypes/disk-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-compute-list| [disk-list:success](ActivityTypes/disk-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-volume-modify-failed| [disk-modify:fail](ActivityTypes/disk-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-volume-modify | [disk-modify:success](ActivityTypes/disk-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-disk-write| [disk-write:success](ActivityTypes/disk-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| image-loaded| [dll-load:success](ActivityTypes/dll-load.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| dns-query | [dns-request:success](ActivityTypes/dns-request.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| query| dns_query |
| &nbsp;| &nbsp;| query_flags| dns_query_flags |
| &nbsp;| &nbsp;| query_type | dns_query_type|
| &nbsp;| &nbsp;| response | dns_response|
| &nbsp;| &nbsp;| response_flags | dns_response_flags|
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| dns-response| [dns-response:fail](ActivityTypes/dns-response.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| query| dns_query |
| &nbsp;| &nbsp;| query_flags| dns_query_flags |
| &nbsp;| &nbsp;| query_type | dns_query_type|
| &nbsp;| &nbsp;| response | dns_response|
| &nbsp;| &nbsp;| response_flags | dns_response_flags|
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| dns-response| [dns-response:success](ActivityTypes/dns-response.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| query| dns_query |
| &nbsp;| &nbsp;| query_flags| dns_query_flags |
| &nbsp;| &nbsp;| query_type | dns_query_type|
| &nbsp;| &nbsp;| response | dns_response|
| &nbsp;| &nbsp;| response_flags | dns_response_flags|
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| network-connection-successful | [dns-traffic:success](ActivityTypes/dns-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| age_of_conn| connection_age|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user_id, uid | user_id |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| computer-logon| [dns_record-modify:success](ActivityTypes/dns_record-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| uids | user_uids |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| failed-ds-access| [ds_object-activity:fail](ActivityTypes/ds_object-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-activity:success](ActivityTypes/ds_object-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-create:success](ActivityTypes/ds_object-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-delete:success](ActivityTypes/ds_object-delete.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-modify:success](ActivityTypes/ds_object-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-move:success](ActivityTypes/ds_object-move.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| ds-access | [ds_object-restore:success](ActivityTypes/ds_object-restore.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| object_class | ds_object_class |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| dlp-email-alert-in-failed | [email-receive:fail](ActivityTypes/email-receive.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| external_domain_recipient| dest_email_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| app, app_name| app |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| external_domain_sender, email_domain | email_domain|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user, suser| user|
| dlp-email-alert-in| [email-receive:success](ActivityTypes/email-receive.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| external_domain_recipient| dest_email_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| app, app_name| app |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| external_domain_sender, email_domain | email_domain|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user, suser| user|
| dlp-email-alert-out-failed| [email-send:fail](ActivityTypes/email-send.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| external_domain_recipient| dest_email_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| app, app_name| app |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| external_domain_sender, email_domain | email_domain|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user, suser| user|
| dlp-email-alert-out | [email-send:success](ActivityTypes/email-send.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| external_domain_recipient| dest_email_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| app, app_name| app |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| external_domain_sender, email_domain | email_domain|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user, suser| user|
| nac-failed-logon| [endpoint-authentication:fail](ActivityTypes/endpoint-authentication.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| authentication-failed | [endpoint-authentication:fail](ActivityTypes/endpoint-authentication.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| authentication-successful | [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| kerberos-logon| [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| nac-logon | [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| aws-instance-create-failed| [endpoint-create:fail](ActivityTypes/endpoint-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-instance-create | [endpoint-create:success](ActivityTypes/endpoint-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-create | [endpoint-create:success](ActivityTypes/endpoint-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-compute-list-failed | [endpoint-list:fail](ActivityTypes/endpoint-list.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-compute-list| [endpoint-list:success](ActivityTypes/endpoint-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-compute-list| [endpoint-list:success](ActivityTypes/endpoint-list.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| workstation-locked| [endpoint-lock:success](ActivityTypes/endpoint-lock.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| failed-logon| [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| account_used_id, account_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| authentication-failed | [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| local-logon | [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_info | user_info |
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| account_used_id, account_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| logon_type, login_type | login_type|
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| nac-failed-logon| [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| remote-logon| [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_id | user_id |
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| computer-logon| [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| uids | user_uids |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| batch-logon | [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| remote-access | [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_logon_id| dest_login_id |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| uuid | user_uid|
| &nbsp;| &nbsp;| account_logon_guid, account_login_guid | account_login_guid|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_service_name, dest_service| dest_service_name |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| aws-instance-login-failed | [endpoint-login:fail](ActivityTypes/endpoint-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| authentication-successful | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| local-logon | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_info | user_info |
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| account_used_id, account_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| logon_type, login_type | login_type|
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| remote-logon| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_id | user_id |
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| computer-logon| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| uids | user_uids |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| batch-logon | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| service-logon | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_logon_id| dest_login_id |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| remote-access | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_logon_id| dest_login_id |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| uuid | user_uid|
| &nbsp;| &nbsp;| account_logon_guid, account_login_guid | account_login_guid|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_service_name, dest_service| dest_service_name |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| ntlm-logon| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_type | user_type |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| kerberos-logon| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| nac-logon | [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| app-activity| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| aws-instance-login| [endpoint-login:success](ActivityTypes/endpoint-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| logout-remote | [endpoint-logout:success](ActivityTypes/endpoint-logout.md) | accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| winsession-disconnect | [endpoint-logout:success](ActivityTypes/endpoint-logout.md) | accesses | access|
| &nbsp;| &nbsp;| description| additional_info |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-modify-failed| [endpoint-modify:fail](ActivityTypes/endpoint-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-instance-setmachinetype | [endpoint-modify:success](ActivityTypes/endpoint-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-instance-setmetadata| [endpoint-modify:success](ActivityTypes/endpoint-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-modify | [endpoint-modify:success](ActivityTypes/endpoint-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [endpoint-notification:success](ActivityTypes/endpoint-notification.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| nac-logon | [endpoint-policy-verify:success](ActivityTypes/endpoint-policy-verify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| gcp-instance-screenshot | [endpoint-screenshot:success](ActivityTypes/endpoint-screenshot.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| workstation-unlocked| [endpoint-unlock:success](ActivityTypes/endpoint-unlock.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-close| [file-close:success](ActivityTypes/file-close.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storageobject-copy-failed | [file-copy:fail](ActivityTypes/file-copy.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storageobject-copy| [file-copy:success](ActivityTypes/file-copy.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-write| [file-copy:success](ActivityTypes/file-copy.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| file-delete | [file-delete:fail](ActivityTypes/file-delete.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-delete | [file-delete:success](ActivityTypes/file-delete.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-download | [file-download:success](ActivityTypes/file-download.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_sid, sid| user_sid|
| gcp-storage-list| [file-list:success](ActivityTypes/file-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-storage-list| [file-list:success](ActivityTypes/file-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| file-move | [file-move:success](ActivityTypes/file-move.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| file-permission-change| [file-permission-modify:success](ActivityTypes/file-permission-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-storageobject-acl | [file-permission-modify:success](ActivityTypes/file-permission-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-container-acl | [file-permission-modify:success](ActivityTypes/file-permission-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| file-read | [file-read:fail](ActivityTypes/file-read.md)| accesses | access|
| &nbsp;| &nbsp;| conn_uids| connection_uid|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| last_name, user_lastname | last_name |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storageobject-read-failed | [file-read:fail](ActivityTypes/file-read.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-read | [file-read:success](ActivityTypes/file-read.md) | accesses | access|
| &nbsp;| &nbsp;| conn_uids| connection_uid|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| last_name, user_lastname | last_name |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| usb-read| [file-read:success](ActivityTypes/file-read.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-storageobject-read| [file-read:success](ActivityTypes/file-read.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-blob-read | [file-read:success](ActivityTypes/file-read.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-storageobject-read| [file-read:success](ActivityTypes/file-read.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-write| [file-rename:success](ActivityTypes/file-rename.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| file-share| [file-share:success](ActivityTypes/file-share.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| file-upload | [file-upload:success](ActivityTypes/file-upload.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-write| [file-write:fail](ActivityTypes/file-write.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| aws-storageobject-write-failed| [file-write:fail](ActivityTypes/file-write.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-write| [file-write:success](ActivityTypes/file-write.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| usb-write | [file-write:success](ActivityTypes/file-write.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| last_name, user_lastname | last_name |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-storageobject-write | [file-write:success](ActivityTypes/file-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-blob-write| [file-write:success](ActivityTypes/file-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-storageobject-write | [file-write:success](ActivityTypes/file-write.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-function-write-failed | [function-write:fail](ActivityTypes/function-write.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-function-write| [function-write:success](ActivityTypes/function-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-function-write| [function-write:success](ActivityTypes/function-write.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-list-failed| [group-list:fail](ActivityTypes/group-list.md)| bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-identity-list | [group-list:success](ActivityTypes/group-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-identity-addtogroup-failed| [group-member-add:fail](ActivityTypes/group-member-add.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| member-added| [group-member-add:success](ActivityTypes/group-member-add.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_dn | user_dn |
| &nbsp;| &nbsp;| account_ou | user_ou |
| &nbsp;| &nbsp;| account_used_domain, account_domain| account_domain|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| user_domain, domain| domain|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| aws-identity-addtogroup | [group-member-add:success](ActivityTypes/group-member-add.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| member-removed| [group-member-remove:success](ActivityTypes/group-member-remove.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_dn | user_dn |
| &nbsp;| &nbsp;| account_ou | user_ou |
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| aws-policy-attach | [group-policy-attach:success](ActivityTypes/group-policy-attach.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity-failed | [http-request:fail](ActivityTypes/http-request.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| app-activity| [http-request:success](ActivityTypes/http-request.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| web-activity-denied | [http-session:fail](ActivityTypes/http-session.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| risk_level, alert_severity | alert_severity|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-activity-allowed| [http-session:success](ActivityTypes/http-session.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| risk_level, alert_severity | alert_severity|
| &nbsp;| &nbsp;| app_class, app_group | app_group |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-image-create-failed | [image-create:fail](ActivityTypes/image-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-image-create| [image-create:success](ActivityTypes/image-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-image-create| [image-create:success](ActivityTypes/image-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-image-modify-failed | [image-modify:fail](ActivityTypes/image-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-image-modify| [image-modify:success](ActivityTypes/image-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-instance-write| [image-write:success](ActivityTypes/image-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| azure-image-write | [image-write:success](ActivityTypes/image-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-instance-creds-read-failed| [key-read:fail](ActivityTypes/key-read.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-keyvault-read | [key-read:success](ActivityTypes/key-read.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-instance-creds-read | [key-read:success](ActivityTypes/key-read.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-creds-write-failed | [key-write:fail](ActivityTypes/key-write.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-instance-creds-write| [key-write:success](ActivityTypes/key-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| azure-keyvault-write| [key-write:success](ActivityTypes/key-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-instance-creds-write| [key-write:success](ActivityTypes/key-write.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| audit-log-clear | [log-clear:success](ActivityTypes/log-clear.md) | accesses | access|
| &nbsp;| &nbsp;| policy | audit_policy_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-meeting-created | [meeting-create:success](ActivityTypes/meeting-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-meeting-ended | [meeting-end:success](ActivityTypes/meeting-end.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-meeting-participant-joined| [meeting-member-join:success](ActivityTypes/meeting-member-join.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-meeting-updated | [meeting-modify:success](ActivityTypes/meeting-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| web-meeting-started | [meeting-start:success](ActivityTypes/meeting-start.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| network-connection-failed | [network-close:success](ActivityTypes/network-close.md) | accesses | access|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_id, uid | user_id |
| network-info| [network-notification:success](ActivityTypes/network-notification.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| network-connection-failed | [network-session:fail](ActivityTypes/network-session.md)| accesses | access|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_id, uid | user_id |
| process-network-failed| [network-session:fail](ActivityTypes/network-session.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_process_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_path|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| netflow-connection| [network-session:success](ActivityTypes/network-session.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| process-network | [network-session:success](ActivityTypes/network-session.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_process_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_path|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| network-connection-successful | [network-session:success](ActivityTypes/network-session.md) | accesses | access|
| &nbsp;| &nbsp;| age_of_conn| connection_age|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user_id, uid | user_id |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| network-connection-failed | [network-traffic:fail](ActivityTypes/network-traffic.md)| accesses | access|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_id, uid | user_id |
| network-connection-successful | [network-traffic:success](ActivityTypes/network-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| age_of_conn| connection_age|
| &nbsp;| &nbsp;| conn_state | connection_state|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| dest_ip, remote_ip | dest_ip |
| &nbsp;| &nbsp;| dest_port, remote_port | dest_port |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| local_ip, src_ip | src_ip|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| local_port, src_port | src_port|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| user_id, uid | user_id |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| netflow-connection| [network-traffic:success](ActivityTypes/network-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| failed-usb-activity | [peripheral_storage-activity:fail](ActivityTypes/peripheral_storage-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| usb-activity| [peripheral_storage-activity:success](ActivityTypes/peripheral_storage-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| usb-insert| [peripheral_storage-insert:success](ActivityTypes/peripheral_storage-insert.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| failed-physical-access| [physical_location-access:fail](ActivityTypes/physical_location-access.md)| accesses | access|
| &nbsp;| &nbsp;| blockinggroupname| blocking_group_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| user_lastname, last_name | last_name |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| reason, outcome_reason | result_reason |
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| physical-access | [physical_location-access:success](ActivityTypes/physical_location-access.md) | accesses | access|
| &nbsp;| &nbsp;| blockinggroupname| blocking_group_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| user_lastname, last_name | last_name |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| reason, outcome_reason | result_reason |
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-write| [policy-create:fail](ActivityTypes/policy-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-write| [policy-create:success](ActivityTypes/policy-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-list-failed| [policy-list:fail](ActivityTypes/policy-list.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-list | [policy-list:success](ActivityTypes/policy-list.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-setversion-failed| [policy-modify:fail](ActivityTypes/policy-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-role-assumepolicy | [policy-modify:success](ActivityTypes/policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-write| [policy-modify:success](ActivityTypes/policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-setversion | [policy-modify:success](ActivityTypes/policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-policy-write| [policy-modify:success](ActivityTypes/policy-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| print-activity| [printer-activity:success](ActivityTypes/printer-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| num_pages, number_of_page| num_pages |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| process-created-failed| [process-create:fail](ActivityTypes/process-create.md)| accesses | access|
| &nbsp;| &nbsp;| account_used_id| account_id|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| target_process_guid| process_guid|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| process-created | [process-create:success](ActivityTypes/process-create.md) | accesses | access|
| &nbsp;| &nbsp;| account_used_id| account_id|
| &nbsp;| &nbsp;| authentication | auth|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, log_id, event_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_guid, target_process_guid| process_guid|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [process-create:success](ActivityTypes/process-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| nac-failed-logon| [radius-traffic:fail](ActivityTypes/radius-traffic.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| nac-logon | [radius-traffic:success](ActivityTypes/radius-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| computer-logon| [radius-traffic:success](ActivityTypes/radius-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| uids | user_uids |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| description, additional_info | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| remote-logon| [rdp-traffic:success](ActivityTypes/rdp-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_id | user_id |
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| registry-write| [registry-create:success](ActivityTypes/registry-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, event_id, log_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| registry-write| [registry-modify:success](ActivityTypes/registry-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, event_id, log_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [repository-create:success](ActivityTypes/repository-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| app-activity| [repository-modify:success](ActivityTypes/repository-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| aws-role-assume-failed| [role-assume:fail](ActivityTypes/role-assume.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-role-assume | [role-assume:success](ActivityTypes/role-assume.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-role-switch | [role-assume:success](ActivityTypes/role-assume.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-role-write| [role-create:fail](ActivityTypes/role-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-role-write| [role-create:success](ActivityTypes/role-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-role-write| [role-create:success](ActivityTypes/role-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-list-failed| [role-list:fail](ActivityTypes/role-list.md)| bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| gcp-role-list | [role-list:success](ActivityTypes/role-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-list | [role-list:success](ActivityTypes/role-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| gcp-role-write| [role-modify:success](ActivityTypes/role-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-attach | [role-policy-attach:success](ActivityTypes/role-policy-attach.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-role-write| [role-write:success](ActivityTypes/role-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| task-created| [scheduled_task-create:success](ActivityTypes/scheduled_task-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [scheduled_task-finish:success](ActivityTypes/scheduled_task-finish.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| app-activity| [scheduled_task-start:success](ActivityTypes/scheduled_task-start.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| process-created | [script-execute:success](ActivityTypes/script-execute.md) | accesses | access|
| &nbsp;| &nbsp;| account_used_id| account_id|
| &nbsp;| &nbsp;| authentication | auth|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| url| file_url|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, log_id, event_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_guid, target_process_guid| process_guid|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| service-created | [service-create:success](ActivityTypes/service-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| app-activity| [service-stop:success](ActivityTypes/service-stop.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| share-access-denied | [share-access:fail](ActivityTypes/share-access.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| creation_time| time_created|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| share-access| [share-access:success](ActivityTypes/share-access.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| creation_time| time_created|
| &nbsp;| &nbsp;| accesses, accesses_code| access|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| share-access| [share-create:success](ActivityTypes/share-create.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| creation_time| time_created|
| &nbsp;| &nbsp;| accesses, accesses_code| access|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| share-access| [share-delete:success](ActivityTypes/share-delete.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| creation_time| time_created|
| &nbsp;| &nbsp;| accesses, accesses_code| access|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| share-access| [share-modify:success](ActivityTypes/share-modify.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| creation_time| time_created|
| &nbsp;| &nbsp;| accesses, accesses_code| access|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| file-read | [share-mount:success](ActivityTypes/share-mount.md) | accesses | access|
| &nbsp;| &nbsp;| conn_uids| connection_uid|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_uri | file_url|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| user_firstname, first_name | first_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| last_name, user_lastname | last_name |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_pid, parent_process_id| parent_process_id |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-snapshot-create-failed| [snapshot-create:fail](ActivityTypes/snapshot-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-snapshot-create | [snapshot-create:success](ActivityTypes/snapshot-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-snapshot-create | [snapshot-create:success](ActivityTypes/snapshot-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-compute-list| [snapshot-list:success](ActivityTypes/snapshot-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-snapshot-modify-failed| [snapshot-modify:fail](ActivityTypes/snapshot-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-snapshot-modify | [snapshot-modify:success](ActivityTypes/snapshot-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-snapshot-write| [snapshot-write:success](ActivityTypes/snapshot-write.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| remote-logon| [ssh-traffic:success](ActivityTypes/ssh-traffic.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| result_code| http_response_code|
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, record_id | event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_id | user_id |
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| aws-identity-write-failed | [user-create:fail](ActivityTypes/user-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-creation| [user-create:success](ActivityTypes/user-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_used_domain, account_domain| account_domain|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [user-create:success](ActivityTypes/user-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| gcp-serviceaccount-write| [user-create:success](ActivityTypes/user-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-write| [user-create:success](ActivityTypes/user-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-deleted | [user-delete:fail](ActivityTypes/user-delete.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-deleted | [user-delete:success](ActivityTypes/user-delete.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-disabled| [user-disable:success](ActivityTypes/user-disable.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-enabled | [user-enable:success](ActivityTypes/user-enable.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-activity| [user-invite:success](ActivityTypes/user-invite.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| aws-identity-creds-write-failed | [user-key-create:fail](ActivityTypes/user-key-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-serviceaccount-creds-write| [user-key-create:success](ActivityTypes/user-key-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-creds-write| [user-key-create:success](ActivityTypes/user-key-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-list-failed| [user-list:fail](ActivityTypes/user-list.md)| bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| aws-identity-list | [user-list:success](ActivityTypes/user-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| account-lockout | [user-lock:fail](ActivityTypes/user-lock.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| account-lockout | [user-lock:success](ActivityTypes/user-lock.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| account-password-change-failed| [user-password-modify:fail](ActivityTypes/user-password-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-password-change | [user-password-modify:success](ActivityTypes/user-password-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-password-reset| [user-password-reset:fail](ActivityTypes/user-password-reset.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| account-password-reset| [user-password-reset:success](ActivityTypes/user-password-reset.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-policy-attach | [user-policy-attach:success](ActivityTypes/user-policy-attach.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| privileged-access | [user-privilege-assign:success](ActivityTypes/user-privilege-assign.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| additional_info, description | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| privileged-access | [user-privilege-modify:fail](ActivityTypes/user-privilege-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| additional_info, description | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| privileged-access | [user-privilege-modify:success](ActivityTypes/user-privilege-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| additional_info, description | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| privileged-object-access| [user-privilege-use:success](ActivityTypes/user-privilege-use.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| additional_info, description | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| logon_id, login_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| privileged-access | [user-privilege-use:success](ActivityTypes/user-privilege-use.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| additional_info, description | additional_info |
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_id, logon_id | login_id|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| azure-role-assign | [user-role-assign:success](ActivityTypes/user-role-assign.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| account-switch| [user-switch:success](ActivityTypes/user-switch.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| dest_service | dest_service_name |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| account_id, account_used_id| account_id|
| &nbsp;| &nbsp;| account_logon_guid, account_login_guid | account_login_guid|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_guid, target_process_guid| process_guid|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| account-unlocked| [user-unlock:success](ActivityTypes/user-unlock.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_ou, account_ou| user_ou |
| authentication-failed | [vpn-authentication:fail](ActivityTypes/vpn-authentication.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| authentication-successful | [vpn-authentication:success](ActivityTypes/vpn-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| failed-vpn-login| [vpn-login:fail](ActivityTypes/vpn-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| bytes_sent, bytes_out| bytes_out |
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, event_id, log_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| authentication-failed | [vpn-login:fail](ActivityTypes/vpn-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| vpn-login | [vpn-login:success](ActivityTypes/vpn-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| bytes_sent, bytes_out| bytes_out |
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, event_id, log_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user, username | user|
| authentication-successful | [vpn-login:success](ActivityTypes/vpn-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| vpn-connection| [vpn-login:success](ActivityTypes/vpn-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| vpn-logout| [vpn-logout:success](ActivityTypes/vpn-logout.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| group| group_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sconnection_id | source_connection_id|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| bytes_sent, bytes_out| bytes_out |
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| record_id, event_id, log_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| vpn-connection| [vpn-session:success](ActivityTypes/vpn-session.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| directory, file_dir, file_parent, f_parent | file_dir|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|