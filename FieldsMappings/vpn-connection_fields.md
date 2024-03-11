Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: vpn-connection
### New-Scale Activity Type: vpn-login:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields         | New-Scale Fields |
| ------------------ | ---------------- |
| outcome            | action           |
| total_bytes        | bytes            |
| bytes_recieved     | bytes_in         |
| bytes_send         | bytes_out        |
| conn_id            | connection_id    |
| user_email         | email_address    |
| user_firstname     | first_name       |
| user_fullname      | full_name        |
| user_lastname      | last_name        |
| logon_id           | login_id         |
| logon_type         | login_type       |
| status,<br>outcome | result           |