oracle access management
========================

Expression
----------

product = "oracle access management"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| src_ip          |      |           | &#10003;      |
| additional_info |      |           | &#10003;      |
| resource        |      |           | &#10003;      |
| operation       |      |           | &#10003;      |
| object          |      |           | &#10003;      |
| target          |      |           | &#10003;      |

Activity Types
--------------

| Activity Type      | Field        | Status  | Core | Detection | Informational |
| ------------------ | ------------ | ------- | ---- | --------- | ------------- |
| app-authentication | file_path    | Default |      |           | &#10003;      |
|                    | file_ext     | Default |      |           | &#10003;      |
|                    | file_name    | Default |      |           | &#10003;      |
|                    | service_name | Default |      |           | &#10003;      |
|                    | event_code   | Default |      |           | &#10003;      |
|                    | dest_ip      | Default |      | &#10003;  |               |
|                    | file_dir     | Default |      |           | &#10003;      |
|                    | dest_host    | Default |      | &#10003;  |               |
|                    | event_name   | Default |      |           | &#10003;      |
|                    | src_host     | Default |      | &#10003;  |               |
| app-login          | domain       | Default |      |           | &#10003;      |
| app-logout         | domain       | Default |      |           | &#10003;      |
| app-notification   | domain       | Default |      |           | &#10003;      |
|                    | user         | Default |      | &#10003;  |               |

