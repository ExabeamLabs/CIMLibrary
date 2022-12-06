lanscope cat
============

Expression
----------

product = "lanscope cat"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type               | Field        | Status  | Core     | Detection | Informational |
| --------------------------- | ------------ | ------- | -------- | --------- | ------------- |
| alert-trigger               | src_ip       | Legacy  | &#10003; | &#10003;  |               |
|                             | dest_ip      | Legacy  | &#10003; | &#10003;  |               |
|                             | num_pages    |         |          |           |               |
|                             | dest_host    | Legacy  |          | &#10003;  |               |
|                             | printer_name |         |          |           |               |
|                             | src_host     | Legacy  | &#10003; | &#10003;  |               |
|                             | operation    |         |          |           |               |
|                             | user         | Legacy  |          | &#10003;  |               |
|                             | object       |         |          |           |               |
| app-activity                | app          | Default |          |           | &#10003;      |
|                             | file_path    | Default |          |           | &#10003;      |
|                             | file_ext     | Default |          |           | &#10003;      |
|                             | file_name    | Default |          |           | &#10003;      |
|                             | bytes        | Default |          |           | &#10003;      |
|                             | file_dir     | Default |          |           | &#10003;      |
|                             | user         | Default |          | &#10003;  |               |
|                             | object       | Default |          |           | &#10003;      |
| endpoint-login              | src_ip       | Default |          | &#10003;  |               |
| file-read                   | bytes        | Legacy  |          |           | &#10003;      |
| file-write                  | bytes        | Legacy  |          | &#10003;  |               |
| http-session                |              |         |          |           |               |
| peripheral_storage-activity | src_ip       | Default |          | &#10003;  |               |
|                             | process_name | Default |          |           | &#10003;      |
|                             | bytes        | Default |          |           | &#10003;      |
|                             | user         | Default |          | &#10003;  |               |
| printer-activity            | src_ip       |         |          | &#10003;  |               |
|                             | num_pages    | Legacy  |          | &#10003;  |               |
|                             | dest_ip      |         |          | &#10003;  |               |
|                             | dest_host    |         |          | &#10003;  |               |
|                             | printer_name | Legacy  | &#10003; | &#10003;  |               |
|                             | src_host     | Legacy  |          |           | &#10003;      |

