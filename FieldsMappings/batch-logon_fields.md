Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: batch-logon
### New-Scale Activity Type: endpoint-login:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields     | New-Scale Fields |
| -------------- | ---------------- |
| outcome        | action           |
| description    | additional_info  |
| conn_id        | connection_id    |
| target_user    | dest_user        |
| user_email     | email_address    |
| category       | event_category   |
| record_id      | event_code       |
| record_id      | event_id         |
| user_firstname | first_name       |
| user_fullname  | full_name        |
| user_lastname  | last_name        |
| logon_id       | login_id         |
| logon_type     | login_type       |
| outcome        | result           |
| service        | service_name     |
| account_type   | user_type        |