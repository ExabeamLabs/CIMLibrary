cisco firepower
===============

Expression
----------

product = cisco firepower

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ip             |      | &#10003;  |               |
| fallback_user_name |      |           |               |
| user               |      | &#10003;  |               |

Activity Types
--------------

| Activity Type           | Field                 | Status  | Core     | Detection | Informational |
| ----------------------- | --------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger           | classification_name   |         |          |           |               |
|                         | malware_file_name     |         |          |           |               |
|                         | block_type            |         |          |           |               |
|                         | bytes_in              |         |          |           |               |
|                         | rule                  |         |          |           |               |
|                         | result                |         |          |           |               |
|                         | src_ip                | Legacy  | &#10003; | &#10003;  |               |
|                         | egress_security_zone  |         |          |           |               |
|                         | protocol              | Legacy  |          | &#10003;  |               |
|                         | blocked               |         |          |           |               |
|                         | ip_protocl_id         |         |          |           |               |
|                         | file_type             |         |          |           |               |
|                         | process_name          | Legacy  |          | &#10003;  |               |
|                         | alert_id              | Legacy  |          |           | &#10003;      |
|                         | hash_md5              |         |          |           |               |
|                         | app_protocol          |         |          |           |               |
|                         | app_id                |         |          |           |               |
|                         | dest_port             | Legacy  |          | &#10003;  |               |
|                         | direction             |         |          |           |               |
|                         | policy                |         |          |           |               |
|                         | process               |         |          |           |               |
|                         | ioc_number            |         |          |           |               |
|                         | device_id             |         |          |           |               |
|                         | alert_description     |         |          |           |               |
|                         | impact                |         |          |           |               |
|                         | record_type           |         |          |           |               |
|                         | src_port              | Legacy  |          |           | &#10003;      |
|                         | rule_id               |         |          |           |               |
|                         | event_id              |         |          |           |               |
|                         | bytes_out             |         |          |           |               |
|                         | additional_info       |         |          |           |               |
|                         | src_country           |         |          |           |               |
|                         | user_id               |         |          |           |               |
|                         | bytes                 | Legacy  |          | &#10003;  |               |
|                         | dest_ip               | Legacy  | &#10003; | &#10003;  |               |
|                         | dest_host             | Legacy  |          | &#10003;  |               |
|                         | ingress_interface     |         |          |           |               |
|                         | malware_url           |         |          |           |               |
|                         | sensor                |         |          |           |               |
|                         | user                  | Legacy  |          | &#10003;  |               |
|                         | connection_counter    |         |          |           |               |
|                         | dest_country          |         |          |           |               |
|                         | ingress_security_zone |         |          |           |               |
| dns-request             | src_interface         |         |          | &#10003;  |               |
|                         | dns_record_type       |         |          | &#10003;  |               |
|                         | response_ttl          |         |          | &#10003;  |               |
|                         | dest_interface        |         |          | &#10003;  |               |
|                         | bytes_in              |         |          | &#10003;  |               |
|                         | rule                  |         |          | &#10003;  |               |
|                         | protocol              |         |          | &#10003;  |               |
|                         | bytes_out             |         |          | &#10003;  |               |
|                         | bytes                 | Legacy  |          | &#10003;  |               |
|                         | action                |         |          | &#10003;  |               |
|                         | dns_response_type     |         |          | &#10003;  |               |
|                         | category              |         |          | &#10003;  |               |
|                         | policy                |         |          | &#10003;  |               |
| dns-response            | result                |         |          | &#10003;  |               |
|                         | src_interface         |         |          | &#10003;  |               |
|                         | egress_zone           |         |          | &#10003;  |               |
|                         | protocol              |         |          | &#10003;  |               |
|                         | bytes_out             |         |          | &#10003;  |               |
|                         | dest_interface        |         |          | &#10003;  |               |
|                         | bytes_in              |         |          | &#10003;  |               |
|                         | ingress_zone          |         |          | &#10003;  |               |
|                         | alert_type            |         |          | &#10003;  |               |
|                         | policy                |         |          | &#10003;  |               |
| endpoint-authentication | event_code            | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
| http-session            | src_interface         | Default |          |           | &#10003;      |
|                         | protocol              | Default |          |           | &#10003;      |
|                         | dest_interface        | Default |          |           | &#10003;      |
|                         | app_protocol          | Default |          |           | &#10003;      |
|                         | rule                  | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
|                         | alert_name            | Default |          |           | &#10003;      |
|                         | policy                | Default |          |           | &#10003;      |
| network-session         | src_interface         | Default |          |           | &#10003;      |
|                         | egress_zone           | Default |          |           | &#10003;      |
|                         | responder_packets     | Default |          |           | &#10003;      |
|                         | packets_out           | Default |          |           | &#10003;      |
|                         | bytes_in              | Default |          |           | &#10003;      |
|                         | network_app           | Default |          |           | &#10003;      |
|                         | nap_policy            | Default |          |           | &#10003;      |
|                         | response_type         | Default |          |           | &#10003;      |
|                         | reputation            | Default |          |           | &#10003;      |
|                         | rule                  | Default |          |           | &#10003;      |
|                         | result                | Default |          |           | &#10003;      |
|                         | tcp_flags             | Default |          |           | &#10003;      |
|                         | event_code            | Default |          |           | &#10003;      |
|                         | initiator_packets     | Default |          |           | &#10003;      |
|                         | connection_duration   | Default |          |           | &#10003;      |
|                         | app_protocol          | Default |          |           | &#10003;      |
|                         | action                | Default |          |           | &#10003;      |
|                         | policy                | Default |          |           | &#10003;      |
|                         | connection_type       | Default |          |           | &#10003;      |
|                         | device_id             | Default |          |           | &#10003;      |
|                         | dest_interface        | Default |          |           | &#10003;      |
|                         | packets_in            | Default |          |           | &#10003;      |
|                         | ingress_zone          | Default |          |           | &#10003;      |
|                         | url                   | Default |          |           | &#10003;      |
|                         | bytes_out             | Default |          |           | &#10003;      |
|                         | additional_info       | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | category              | Default |          |           | &#10003;      |
| vpn-authentication      | event_code            | Default |          |           | &#10003;      |
|                         | event_name            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |
| vpn-login               | group_name            | Default |          |           | &#10003;      |
|                         | event_code            | Default |          |           | &#10003;      |
|                         | priority              | Default |          |           | &#10003;      |

