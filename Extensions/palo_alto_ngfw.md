palo alto ngfw
==============

Expression
----------

product = "palo alto ngfw"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type        | Field             | Status  | Core | Detection | Informational |
| -------------------- | ----------------- | ------- | ---- | --------- | ------------- |
| app-login            | src_ip            | Default |      | &#10003;  |               |
|                      | src_host          | Default |      | &#10003;  |               |
| configuration-modify | src_ip            |         |      | &#10003;  |               |
|                      | src_host          |         |      | &#10003;  |               |
|                      | operation         |         |      |           | &#10003;      |
|                      | object            |         |      |           | &#10003;      |
| http-session         | src_network_zone  | Default |      |           | &#10003;      |
|                      | network_app       | Default |      |           | &#10003;      |
|                      | dest_network_zone | Default |      |           | &#10003;      |
| network-session      | src_network_zone  | Default |      |           | &#10003;      |
|                      | bytes_in          | Default |      |           | &#10003;      |
|                      | rule              | Default |      |           | &#10003;      |
|                      | network_app       | Default |      |           | &#10003;      |
|                      | dest_user         | Default |      | &#10003;  |               |
|                      | dest_network_zone | Default |      |           | &#10003;      |
|                      | bytes_out         | Default |      |           | &#10003;      |
|                      | src_country       | Default |      |           | &#10003;      |
|                      | domain            | Default |      |           | &#10003;      |
|                      | dest_domain       | Default |      |           | &#10003;      |
|                      | action            | Default |      |           | &#10003;      |
|                      | category          | Default |      |           | &#10003;      |
|                      | user              | Default |      | &#10003;  |               |
|                      | dest_country      | Default |      |           | &#10003;      |
|                      | direction         | Default |      |           | &#10003;      |

