Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: network-connection-successful
### New-Scale Activity Type: dns-traffic:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields        | New-Scale Fields     |
| ----------------- | -------------------- |
| accesses          | access               |
| outcome           | action               |
| bytes_recieved    | bytes_in             |
| bytes_send        | bytes_out            |
| conn_id           | connection_id        |
| conn_state        | connection_state     |
| remote_ip         | dest_ip              |
| remote_port       | dest_port            |
| user_email        | email_address        |
| file_parent       | file_dir             |
| user_firstname    | first_name           |
| user_fullname     | full_name            |
| user_lastname     | last_name            |
| logon_id          | login_id             |
| logon_type        | login_type           |
| activity          | operation            |
| activity_type     | operation_type       |
| policy            | policy_name          |
| command_line      | process_command_line |
| process_directory | process_dir          |
| pid               | process_id           |
| process           | process_path         |
| proto             | protocol             |
| outcome           | result               |
| service           | service_name         |
| file_path         | src_file_path        |
| local_ip          | src_ip               |
| local_port        | src_port             |
| uid               | user_id              |