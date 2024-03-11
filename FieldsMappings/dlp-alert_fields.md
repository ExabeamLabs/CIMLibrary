Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: dlp-alert
### New-Scale Activity Type: alert-trigger:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields            | New-Scale Fields     |
| --------------------- | -------------------- |
| accesses              | access               |
| outcome               | action               |
| subject               | alert_subject        |
| conn_id               | connection_id        |
| recipients            | email_recipients     |
| subject               | email_subject        |
| record_id             | event_id             |
| user_firstname        | first_name           |
| user_fullname         | full_name            |
| hash_md5              | hash_md5             |
| sha1                  | hash_sha1            |
| user_lastname         | last_name            |
| logon_id              | login_id             |
| logon_type            | login_type           |
| activity              | operation            |
| policy                | policy_name          |
| command_line          | process_command_line |
| directory             | process_dir          |
| process               | process_path         |
| outcome               | result               |
| service               | service_name         |
| malware_url           | url                  |
| suser                 | user                 |
| sender,<br>user_email | event_id             |
| sha256,<br>sha256_sum | hash_sha256          |