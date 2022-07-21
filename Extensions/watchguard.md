watchguard
==========

Expression
----------

product = "watchguard"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| bytes_out |      |           | &#10003;      |
| bytes_in  |      |           | &#10003;      |
| domain    |      |           | &#10003;      |
| category  |      |           | &#10003;      |
| user      |      |           | &#10003;      |

Activity Types
--------------

| Activity Type   | Field        | Status  | Core | Detection | Informational |
| --------------- | ------------ | ------- | ---- | --------- | ------------- |
| http-session    | proxy_action | Default |      |           | &#10003;      |
| network-session | web_domain   | Default |      |           | &#10003;      |
|                 | event_code   | Default |      |           | &#10003;      |
|                 | operation    | Default |      |           | &#10003;      |

