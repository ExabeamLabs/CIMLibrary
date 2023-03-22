titanftp
========

Expression
----------

product = "titanftp"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      |           | &#10003;      |
| src_port  |      |           | &#10003;      |
| access    |      |           | &#10003;      |
| bytes     |      |           | &#10003;      |
| dest_ip   |      |           | &#10003;      |
| user      |      |           | &#10003;      |
| dest_port |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field     | Status  | Core | Detection | Informational |
| ------------- | --------- | ------- | ---- | --------- | ------------- |
| file-delete   |           |         |      |           |               |
| file-read     |           |         |      |           |               |
| ftp-traffic   | file_path | Default |      |           | &#10003;      |
|               | file_ext  | Default |      |           | &#10003;      |
|               | file_name | Default |      |           | &#10003;      |

