tanium core platform
====================

Expression
----------

product = "tanium core platform"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field        | Status  | Core | Detection | Informational |
| ----------------------- | ------------ | ------- | ---- | --------- | ------------- |
| dns-response            | process_name |         |      |           |               |
|                         | process_dir  |         |      |           |               |
|                         | src_host     | Legacy  |      |           | &#10003;      |
|                         | process_path |         |      |           |               |
| endpoint-authentication | src_ip       | Default |      | &#10003;  |               |
|                         | auth_method  | Default |      |           | &#10003;      |
|                         | process_name | Default |      |           | &#10003;      |
|                         | process_dir  | Default |      |           | &#10003;      |
|                         | process_path | Default |      |           | &#10003;      |
| process-create          | domain       | Default |      |           | &#10003;      |
|                         | hash_md5     | Default |      |           | &#10003;      |
|                         | user         | Default |      | &#10003;  |               |

