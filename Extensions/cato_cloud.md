cato cloud
==========

Expression
----------

product = "cato cloud"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field        | Status  | Core | Detection | Informational |
| ------------- | ------------ | ------- | ---- | --------- | ------------- |
| http-session  | src_country  | Default |      |           | &#10003;      |
|               | src_host     | Default |      | &#10003;  |               |
|               | dest_country | Default |      |           | &#10003;      |
| vpn-login     | os           | Default |      |           | &#10003;      |
|               | dest_ip      | Default |      | &#10003;  |               |
| vpn-logout    | os           |         |      |           | &#10003;      |
|               | dest_ip      |         |      | &#10003;  |               |

