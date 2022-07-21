eset endpoint security
======================

Expression
----------

product = "eset endpoint security"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field           | Status  | Core | Detection | Informational |
| ----------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-login               | process_dir     | Default |      |           | &#10003;      |
|                         | url             | Default |      |           | &#10003;      |
|                         | hash_sha256     | Default |      |           | &#10003;      |
|                         | src_port        | Default |      |           | &#10003;      |
|                         | src_ip          | Default |      | &#10003;  |               |
|                         | protocol        | Default |      |           | &#10003;      |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | process_name    | Default |      |           | &#10003;      |
|                         | dest_ip         | Default |      | &#10003;  |               |
|                         | event_name      | Default |      |           | &#10003;      |
|                         | action          | Default |      |           | &#10003;      |
|                         | process_path    | Default |      |           | &#10003;      |
|                         | category        | Default |      |           | &#10003;      |
|                         | dest_port       | Default |      |           | &#10003;      |
|                         | direction       | Default |      |           | &#10003;      |
| endpoint-authentication | src_ip          | Default |      | &#10003;  |               |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | service_name    | Default |      |           | &#10003;      |
|                         | alert_severity  | Default |      |           | &#10003;      |
|                         | event_name      | Default |      |           | &#10003;      |
|                         | category        | Default |      |           | &#10003;      |
|                         | operation       | Default |      |           | &#10003;      |
|                         | object          | Default |      |           | &#10003;      |
| http-session            | hash_sha256     | Default |      |           | &#10003;      |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | process_name    | Default |      |           | &#10003;      |
|                         | domain          | Default |      |           | &#10003;      |
|                         | event_name      | Default |      |           | &#10003;      |
|                         | process_dir     | Default |      |           | &#10003;      |
|                         | process_path    | Default |      |           | &#10003;      |
|                         | direction       | Default |      |           | &#10003;      |

