Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: computer-logon
### New-Scale Activity Type: dhcp-session:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields              | New-Scale Fields |
| ----------------------- | ---------------- |
| user_email              | email_address    |
| category                | event_category   |
| record_id               | event_id         |
| logon_type              | login_type       |
| service                 | service_name     |
| sid                     | user_sid         |
| account_type            | user_type        |
| src_mac_address,<br>mac | src_mac          |