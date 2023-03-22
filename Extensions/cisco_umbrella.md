cisco umbrella
==============

Expression
----------

product = "cisco umbrella"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      | &#10003;  |               |
| category  |      | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field         | Status  | Core | Detection | Informational |
| --------------- | ------------- | ------- | ---- | --------- | ------------- |
| dns-response    | identities    |         |      |           | &#10003;      |
|                 | domain        |         |      | &#10003;  |               |
|                 | src_host      | Legacy  |      |           | &#10003;      |
|                 | categories    |         |      | &#10003;  |               |
|                 | user          | Legacy  |      |           | &#10003;      |
| http-session    | protocol      | Default |      |           | &#10003;      |
|                 | domain        | Default |      |           | &#10003;      |
|                 | result_code   | Default |      |           | &#10003;      |
|                 | categories    | Default |      |           | &#10003;      |
|                 | identity_type | Default |      |           | &#10003;      |
|                 | sha           | Default |      |           | &#10003;      |
| network-traffic |               |         |      |           |               |

