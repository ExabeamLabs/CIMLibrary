Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: failed-vpn-login
### New-Scale Activity Type: vpn-login:fail

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields         | New-Scale Fields |
| ------------------ | ---------------- |
| accesses           | access           |
| outcome            | action           |
| file_size          | bytes            |
| conn_id            | connection_id    |
| target_user        | dest_user        |
| user_email         | email_address    |
| log_type           | event_category   |
| record_id          | event_id         |
| sub_event_type     | event_subtype    |
| user_firstname     | first_name       |
| user_fullname      | full_name        |
| user_lastname      | last_name        |
| logon_id           | login_id         |
| logon_type         | login_type       |
| activity           | operation        |
| policy             | policy_name      |
| pid                | process_id       |
| status             | result           |
| service            | service_name     |
| status,<br>outcome | result           |