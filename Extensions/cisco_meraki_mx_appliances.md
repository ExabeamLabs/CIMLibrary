cisco meraki mx appliances
==========================

Expression
----------

product = "cisco meraki mx appliance"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type   | Field                | Status  | Core | Detection | Informational |
| --------------- | -------------------- | ------- | ---- | --------- | ------------- |
| http-session    | src_mac              | Default |      |           | &#10003;      |
|                 | protocol             | Default |      |           | &#10003;      |
| network-traffic | result               | Default |      |           | &#10003;      |
|                 | duration             | Default |      |           | &#10003;      |
|                 | src_translated_ip    | Default |      |           | &#10003;      |
|                 | domain               | Default |      |           | &#10003;      |
|                 | channel              | Default |      |           | &#10003;      |
|                 | dest_translated_port | Default |      |           | &#10003;      |
|                 | dhcp_ip              | Default |      |           | &#10003;      |
|                 | src_translated_port  | Default |      |           | &#10003;      |
|                 | operation            | Default |      |           | &#10003;      |
|                 | aid                  | Default |      |           | &#10003;      |
|                 | user                 | Default |      | &#10003;  |               |
|                 | dest_translated_ip   | Default |      |           | &#10003;      |
| vpn-login       | src_translated_ip    | Default |      |           | &#10003;      |
| vpn-logout      | src_translated_ip    |         |      | &#10003;  |               |

