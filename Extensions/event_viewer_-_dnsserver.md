event viewer - dnsserver
========================

Expression
----------

product = "event viewer - dnsserver"

Fields
------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| result       |      | &#10003;  |               |
| process_id   |      |           | &#10003;      |
| protocol     |      |           | &#10003;      |
| bytes_out    |      |           | &#10003;      |
| dns_query_id |      |           | &#10003;      |
| operation    |      | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field | Status | Core | Detection | Informational |
| ------------- | ----- | ------ | ---- | --------- | ------------- |
| dns-request   |       |        |      |           |               |
| dns-response  |       |        |      |           |               |

