splunk stream
=============

Expression
----------

product = "splunk stream"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_mac   |      |           | &#10003;      |
| bytes_out |      |           | &#10003;      |
| dest_mac  |      |           | &#10003;      |
| bytes_in  |      |           | &#10003;      |
| bytes     |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field          | Status | Core | Detection | Informational |
| ------------- | -------------- | ------ | ---- | --------- | ------------- |
| dhcp-session  | ip_lease_time  |        |      |           |               |
|               | domain         |        |      |           |               |
|               | dns_ip_flow    |        |      |           |               |
|               | event_name     |        |      |           |               |
|               | trans_id       |        |      |           |               |
|               | router_subnet  |        |      |           |               |
|               | router_ip_flow |        |      |           |               |
| dns-response  | response_ttl   |        |      |           |               |
|               | time_taken     |        |      |           |               |

