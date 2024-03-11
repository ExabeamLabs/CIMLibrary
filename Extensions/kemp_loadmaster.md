kemp loadmaster
===============

Expression
----------

product = "kemp loadmaster"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type      | Field     | Status  | Core | Detection | Informational |
| ------------------ | --------- | ------- | ---- | --------- | ------------- |
| app-activity       | src_port  | Default |      |           | &#10003;      |
|                    | src_ip    | Default |      | &#10003;  |               |
|                    | dest_ip   | Default |      | &#10003;  |               |
|                    | domain    | Default |      |           | &#10003;      |
|                    | user      | Default |      | &#10003;  |               |
|                    | dest_port | Default |      |           | &#10003;      |
|                    | object    | Default |      |           | &#10003;      |
| app-authentication | dest_ip   | Default |      | &#10003;  |               |
|                    | operation | Default |      |           | &#10003;      |
| app-login          | src_ip    | Default |      | &#10003;  |               |
|                    | dest_ip   | Default |      | &#10003;  |               |
|                    | dest_host | Default |      | &#10003;  |               |
|                    | src_host  | Default |      | &#10003;  |               |
| http-request       | domain    | Default |      |           | &#10003;      |
|                    | operation | Default |      |           | &#10003;      |
|                    | object    | Default |      |           | &#10003;      |

