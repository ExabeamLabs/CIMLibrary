cloudflare waf
==============

Expression
----------

product = "cloudflare waf"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type   | Field                  | Status  | Core | Detection | Informational |
| --------------- | ---------------------- | ------- | ---- | --------- | ------------- |
| http-session    | src_country            | Default |      |           | &#10003;      |
|                 | additional_info        | Default |      |           | &#10003;      |
|                 | event_code             | Default |      |           | &#10003;      |
|                 | origin_response_status | Default |      |           | &#10003;      |
|                 | dest_host              | Default |      | &#10003;  |               |
|                 | edge_response_status   | Default |      |           | &#10003;      |
|                 | device_type            | Default |      |           | &#10003;      |
|                 | proxy_action           | Default |      |           | &#10003;      |
| network-session | country_code           | Default |      |           | &#10003;      |
|                 | src_interface          | Default |      |           | &#10003;      |
|                 | method                 | Default |      |           | &#10003;      |
|                 | process_name           | Default |      |           | &#10003;      |
|                 | log_source             | Default |      |           | &#10003;      |
|                 | dest_host              | Default |      | &#10003;  |               |
|                 | category               | Default |      |           | &#10003;      |
|                 | user                   | Default |      | &#10003;  |               |
|                 | user_agent             | Default |      |           | &#10003;      |
|                 | direction              | Default |      |           | &#10003;      |

