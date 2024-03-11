Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: authentication-failed
### New-Scale Activity Type: app-authentication:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                  | New-Scale Fields |
| --------------------------- | ---------------- |
| accesses                    | access           |
| app_name                    | app              |
| file_size                   | bytes            |
| conn_id                     | connection_id    |
| target_user                 | dest_user        |
| user_email                  | email_address    |
| record_id                   | event_id         |
| sub_event_type              | event_subtype    |
| file_parent                 | file_dir         |
| ext                         | file_ext         |
| user_firstname              | first_name       |
| user_fullname               | full_name        |
| user_lastname               | last_name        |
| logon_id                    | login_id         |
| logon_type                  | login_type       |
| activity                    | operation        |
| policy                      | policy_name      |
| pid                         | process_id       |
| service                     | service_name     |
| object_dn                   | src_ds_object_dn |
| object_ou                   | src_ds_object_ou |
| activity_action,<br>outcome | action           |
| status,<br>outcome          | result           |