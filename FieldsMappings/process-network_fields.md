Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: process-network
### New-Scale Activity Type: network-session:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields               | New-Scale Fields            |
| ------------------------ | --------------------------- |
| outcome                  | action                      |
| conn_id                  | connection_id               |
| target_process_directory | dest_process_dir            |
| target_process_guid      | dest_process_guid           |
| target_pid               | dest_process_id             |
| target_process_name      | dest_process_name           |
| target_process           | dest_process_path           |
| user_email               | email_address               |
| file_parent              | file_dir                    |
| user_firstname           | first_name                  |
| user_fullname            | full_name                   |
| grandparent_process      | grandparent_process_path    |
| hash_md5                 | hash_md5                    |
| sha1                     | hash_sha1                   |
| user_lastname            | last_name                   |
| logon_id                 | login_id                    |
| logon_type               | login_type                  |
| activity                 | operation                   |
| parent_command_line      | parent_process_command_line |
| parent_process_directory | parent_process_dir          |
| parent_pid               | parent_process_id           |
| command_line             | process_command_line        |
| pid                      | process_id                  |
| proto                    | protocol                    |
| outcome                  | result                      |
| service                  | service_name                |
| file_path                | src_file_path               |
| sha256,<br>sha256_sum    | hash_sha256                 |