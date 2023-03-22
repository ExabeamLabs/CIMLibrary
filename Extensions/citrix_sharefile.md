citrix sharefile
================

Expression
----------

product = "citrix sharefile"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| src_ip          |      | &#10003;  |               |
| country_code    |      | &#10003;  |               |
| uri_path        |      | &#10003;  |               |
| additional_info |      |           | &#10003;      |
| event_code      |      | &#10003;  |               |
| domain          |      | &#10003;  |               |
| action          |      | &#10003;  |               |
| company         |      | &#10003;  |               |
| user            |      | &#10003;  |               |
| operation       |      | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field     | Status  | Core | Detection | Informational |
| ------------- | --------- | ------- | ---- | --------- | ------------- |
| app-activity  | file_path | Default |      |           | &#10003;      |
|               | file_ext  | Default |      |           | &#10003;      |
|               | file_name | Default |      |           | &#10003;      |
|               | file_dir  | Default |      |           | &#10003;      |
| app-login     |           |         |      |           |               |
| file-download |           |         |      |           |               |
| file-share    | app       | Default |      |           | &#10003;      |
|               | operation | Default |      |           | &#10003;      |
|               | target    | Default |      |           | &#10003;      |
| file-upload   |           |         |      |           |               |

