ftp
===

Expression
----------

product = "ftp"

Fields
------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| src_ip | &#10003; | &#10003;  |               |
| domain |          |           | &#10003;      |
| user   |          | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field  | Status  | Core | Detection | Informational |
| ------------- | ------ | ------- | ---- | --------- | ------------- |
| app-activity  | bytes  | Default |      |           | &#10003;      |
|               | object | Default |      |           | &#10003;      |
| file-delete   |        |         |      |           |               |
| file-read     | bytes  | Legacy  |      |           | &#10003;      |
| file-write    | bytes  | Legacy  |      | &#10003;  |               |

