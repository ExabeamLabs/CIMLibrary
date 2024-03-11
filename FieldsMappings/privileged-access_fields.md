Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: privileged-access
### New-Scale Activity Type: user-privilege-assign:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields        | New-Scale Fields |
| ----------------- | ---------------- |
| accesses          | access           |
| outcome           | action           |
| description       | additional_info  |
| conn_id           | connection_id    |
| target_domain     | dest_domain      |
| target_user       | dest_user        |
| user_email        | email_address    |
| record_id         | event_id         |
| user_firstname    | first_name       |
| user_fullname     | full_name        |
| user_lastname     | last_name        |
| logon_id          | login_id         |
| logon_type        | login_type       |
| activity          | operation        |
| process_directory | process_dir      |
| process           | process_path     |
| outcome           | result           |
| service           | service_name     |