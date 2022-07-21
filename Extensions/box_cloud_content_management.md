box cloud content management
============================

Expression
----------

product = "box cloud content"

Fields
------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| src_ip          |          | &#10003;  |               |
| additional_info |          |           | &#10003;      |
| domain          |          | &#10003;  |               |
| user            | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field        | Status  | Core | Detection | Informational |
| ------------- | ------------ | ------- | ---- | --------- | ------------- |
| app-activity  | application  | Default |      |           | &#10003;      |
|               | resource     | Default |      |           | &#10003;      |
|               | service_name | Default |      |           | &#10003;      |
|               | dest_user    | Default |      | &#10003;  |               |
| app-login     | process_name | Default |      |           | &#10003;      |
|               | event_name   | Default |      |           | &#10003;      |
| file-delete   | owned_user   |         |      | &#10003;  |               |
|               | access_type  |         |      | &#10003;  |               |
|               | access       | Legacy  |      | &#10003;  |               |
|               | file_type    | Legacy  |      |           | &#10003;      |
|               | bytes        |         |      | &#10003;  |               |
|               | object       |         |      | &#10003;  |               |
| file-download | owned_user   |         |      | &#10003;  |               |
|               | access_type  |         |      | &#10003;  |               |
|               | access       |         |      | &#10003;  |               |
|               | file_type    | Legacy  |      |           | &#10003;      |
|               | bytes        | Legacy  |      | &#10003;  |               |
|               | file_dir     | Legacy  |      |           | &#10003;      |
|               | object       |         |      | &#10003;  |               |
| file-read     | owned_user   |         |      | &#10003;  |               |
|               | access_type  |         |      | &#10003;  |               |
|               | access       | Legacy  |      | &#10003;  |               |
|               | file_type    | Legacy  |      |           | &#10003;      |
|               | bytes        | Legacy  |      |           | &#10003;      |
|               | object       |         |      | &#10003;  |               |
| file-upload   | owned_user   |         |      | &#10003;  |               |
|               | access_type  |         |      | &#10003;  |               |
|               | access       |         |      | &#10003;  |               |
|               | application  |         |      |           |               |
|               | resource     |         |      |           |               |
|               | file_type    | Legacy  |      |           | &#10003;      |
|               | bytes        |         |      | &#10003;  |               |
|               | process_name | Legacy  |      |           | &#10003;      |
|               | service_name |         |      |           |               |
|               | dest_user    |         |      |           |               |
|               | object       |         |      | &#10003;  |               |
| file-write    | owned_user   |         |      | &#10003;  |               |
|               | access_type  |         |      | &#10003;  |               |
|               | access       | Legacy  |      | &#10003;  |               |
|               | file_type    | Legacy  |      |           | &#10003;      |
|               | bytes        | Legacy  |      | &#10003;  |               |
|               | process_name | Legacy  |      |           | &#10003;      |
|               | object       |         |      | &#10003;  |               |

