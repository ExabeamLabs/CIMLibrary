Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: remote-logon
### New-Scale Activity Type: endpoint-login:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                      | New-Scale Fields   |
| ------------------------------- | ------------------ |
| outcome                         | action             |
| authentication_package          | auth_package       |
| authentication_process          | auth_process       |
| bytes_recieved                  | bytes_in           |
| bytes_send                      | bytes_out          |
| conn_id                         | connection_id      |
| dest_service                    | dest_service_name  |
| user_email                      | email_address      |
| record_id                       | event_id           |
| user_fullname                   | full_name          |
| group                           | group_name         |
| result_code                     | http_response_code |
| logon_id                        | login_id           |
| logon_type                      | login_type         |
| logon_type_text                 | login_type_text    |
| activity                        | operation          |
| activity_type                   | operation_type     |
| pid                             | process_id         |
| outcome                         | result             |
| account_dn                      | user_dn            |
| sid                             | user_id            |
| account_ou                      | user_ou            |
| bytes_num,<br>bytes_size        | bytes              |
| target_user,<br>tgt_user        | dest_user          |
| process_directory,<br>directory | process_dir        |