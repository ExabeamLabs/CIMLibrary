dropbox
=======

Expression
----------

product = "dropbox"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| src_ip             |          | &#10003;  |               |
| domain             |          |           | &#10003;      |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type          | Field           | Status  | Core | Detection | Informational |
| ---------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity           | additional_info | Default |      |           | &#10003;      |
|                        | resource        | Default |      |           | &#10003;      |
|                        | object          | Default |      |           | &#10003;      |
| app-login              | additional_info | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
| file-delete            | additional_info |         |      |           | &#10003;      |
| file-download          | additional_info |         |      |           | &#10003;      |
| file-permission-modify | src_file_name   |         |      |           | &#10003;      |
|                        | access          | Legacy  |      | &#10003;  |               |
|                        | file_type       | Legacy  |      |           | &#10003;      |
|                        | file_dir_uri    |         |      |           | &#10003;      |
| file-read              | src_file_name   |         |      |           | &#10003;      |
|                        | access          | Legacy  |      | &#10003;  |               |
|                        | additional_info |         |      |           |               |
|                        | file_type       | Legacy  |      |           | &#10003;      |
|                        | file_dir_uri    |         |      |           | &#10003;      |
|                        | operation       |         |      |           |               |
| file-write             | src_file_name   | Legacy  |      | &#10003;  |               |
|                        | access          | Legacy  |      | &#10003;  |               |
|                        | additional_info |         |      |           |               |
|                        | file_type       | Legacy  |      |           | &#10003;      |
|                        | file_dir_uri    |         |      |           | &#10003;      |
|                        | operation       |         |      |           |               |
| report-export          | additional_info | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
| share-mount            | additional_info | Default |      |           | &#10003;      |
|                        | operation       | Default |      |           | &#10003;      |
| user-modify            | additional_info |         |      |           |               |
|                        | operation       |         |      |           |               |

