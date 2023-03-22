barracuda cloudgen firewall
===========================

Expression
----------

product = "barracuda cloudgen firewall"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type   | Field             | Status  | Core | Detection | Informational |
| --------------- | ----------------- | ------- | ---- | --------- | ------------- |
| endpoint-login  | src_ip            | Default |      | &#10003;  |               |
| network-session | duration          | Default |      |           | &#10003;      |
|                 | src_translated_ip | Default |      |           | &#10003;      |
|                 | src_interface     | Default |      |           | &#10003;      |
|                 | dest_external_ip  | Default |      |           | &#10003;      |
|                 | bytes_out         | Default |      |           | &#10003;      |
|                 | dest_interface    | Default |      |           | &#10003;      |
|                 | bytes_in          | Default |      |           | &#10003;      |
|                 | event_code        | Default |      |           | &#10003;      |
|                 | rule              | Default |      |           | &#10003;      |
| vpn-login       | src_port          | Default |      |           | &#10003;      |
|                 | src_translated_ip | Default |      |           | &#10003;      |
|                 | dest_host         | Default |      | &#10003;  |               |
|                 | event_name        | Default |      |           | &#10003;      |

