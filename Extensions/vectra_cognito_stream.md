vectra cognito stream
=====================

Expression
----------

product = "vectra cognito stream"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      |           | &#10003;      |
| src_host  |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field                 | Status  | Core | Detection | Informational |
| ------------- | --------------------- | ------- | ---- | --------- | ------------- |
| app-activity  | src_ip                | Default |      | &#10003;  |               |
|               | result                | Default |      |           | &#10003;      |
|               | app                   | Default |      |           | &#10003;      |
|               | dest_ip               | Default |      | &#10003;  |               |
| rdp-traffic   |                       |         |      |           |               |
| ssh-traffic   | cipher_algorithm      |         |      |           |               |
|               | compression_algotithm |         |      |           |               |
|               | server_version        |         |      |           |               |
|               | client_version        |         |      |           |               |

