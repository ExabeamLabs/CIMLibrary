Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: file-read
### New-Scale Activity Type: file-read:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                | New-Scale Fields     |
| ------------------------- | -------------------- |
| accesses                  | access               |
| outcome                   | action               |
| file_size                 | bytes                |
| target_user               | dest_user            |
| user_email                | email_address        |
| record_id                 | event_id             |
| file_parent               | file_dir             |
| user_firstname            | first_name           |
| user_fullname             | full_name            |
| user_lastname             | last_name            |
| logon_id                  | login_id             |
| activity                  | operation            |
| activity_type             | operation_type       |
| parent_pid                | parent_process_id    |
| policy                    | policy_name          |
| command_line              | process_command_line |
| pid                       | process_id           |
| process                   | process_path         |
| outcome                   | result               |
| service                   | service_name         |
| file_ext                  | src_file_ext         |
| file_name                 | src_file_name        |
| full_url                  | url                  |
| file_path,<br>file_parent | src_file_path        |