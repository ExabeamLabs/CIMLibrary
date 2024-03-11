Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: file-alert
### New-Scale Activity Type: alert-trigger:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                | New-Scale Fields |
| ------------------------- | ---------------- |
| accesses                  | access           |
| outcome                   | action           |
| file_parent               | file_dir         |
| user_firstname            | first_name       |
| hash_md5                  | hash_md5         |
| sha1                      | hash_sha1        |
| user_lastname             | last_name        |
| activity                  | operation        |
| policy                    | policy_name      |
| directory                 | process_dir      |
| process                   | process_path     |
| outcome                   | result           |
| service                   | service_name     |
| malware_url               | url              |
| sha256,<br>sha256_sum     | hash_sha256      |
| file_path,<br>file_parent | src_file_path    |