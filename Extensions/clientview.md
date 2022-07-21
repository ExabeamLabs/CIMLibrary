clientview
==========

Expression
----------

product = "clientview"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type    | Field           | Status  | Core     | Detection | Informational |
| ---------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity     | src_ip          | Default |          | &#10003;  |               |
|                  | additional_info | Default |          |           | &#10003;      |
|                  | domain          | Default |          |           | &#10003;      |
|                  | src_host        | Default |          | &#10003;  |               |
|                  | user            | Default |          | &#10003;  |               |
| email-send       | src_ip          | Default |          | &#10003;  |               |
|                  | src_host        | Default |          | &#10003;  |               |
| file-delete      | src_ip          |         |          |           |               |
|                  | access          | Legacy  |          | &#10003;  |               |
|                  | bytes           |         |          |           |               |
|                  | hash_md5        |         |          |           |               |
|                  | src_host        | Legacy  |          | &#10003;  |               |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
| file-download    | access          |         |          |           |               |
|                  | dest_ip         |         |          |           |               |
|                  | domain          |         |          |           |               |
|                  | dest_host       | Legacy  |          |           | &#10003;      |
|                  | dest_file_dir   |         |          |           |               |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
| file-read        | src_ip          |         |          |           |               |
|                  | access_type     |         |          |           |               |
|                  | access          | Legacy  |          | &#10003;  |               |
|                  | bytes           | Legacy  |          |           | &#10003;      |
|                  | hash_md5        |         |          |           |               |
|                  | src_host        | Legacy  |          | &#10003;  |               |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
| file-upload      | src_ip          |         |          |           |               |
|                  | access          |         |          |           |               |
|                  | domain          |         |          |           |               |
|                  | src_host        | Legacy  |          |           | &#10003;      |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
| file-write       | src_ip          |         |          |           |               |
|                  | access          | Legacy  |          | &#10003;  |               |
|                  | bytes           | Legacy  |          | &#10003;  |               |
|                  | hash_md5        |         |          |           |               |
|                  | src_host        |         |          |           |               |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
| http-session     | src_host        | Default |          | &#10003;  |               |
| printer-activity | src_ip          |         |          |           |               |
|                  | file_path       |         |          |           |               |
|                  | dest_ip         |         |          |           |               |
|                  | num_pages       | Legacy  |          | &#10003;  |               |
|                  | printer_name    | Legacy  | &#10003; | &#10003;  |               |
|                  | src_host        | Legacy  |          |           | &#10003;      |
|                  | user            | Legacy  | &#10003; | &#10003;  |               |
|                  | object          |         |          |           |               |
| process-create   | src_ip          | Default |          | &#10003;  |               |
|                  | hash_md5        | Default |          |           | &#10003;      |
|                  | session_id      | Default |          |           | &#10003;      |
|                  | user            | Default |          | &#10003;  |               |

