check point ngfw
================

Expression
----------

product = "check point ngfw"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| src_ip             | &#10003; | &#10003;  |               |
| dest_ip            | &#10003; | &#10003;  |               |
| local_user_name    |          |           |               |
| fallback_user_name |          |           |               |
| src_host           |          | &#10003;  |               |
| user               |          | &#10003;  |               |

Activity Types
--------------

| Activity Type           | Field                | Status  | Core | Detection | Informational |
| ----------------------- | -------------------- | ------- | ---- | --------- | ------------- |
| app-login               | additional_info      | Default |      |           | &#10003;      |
|                         | user_agent           | Default |      |           | &#10003;      |
| email-receive           | interface_name       | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | src_port             | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | rule_id              | Default |      |           | &#10003;      |
|                         | protocol             | Default |      |           | &#10003;      |
|                         | app_protocol         | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | dest_host            | Default |      | &#10003;  |               |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | dest_port            | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| email-send              | src_interface        | Default |      |           | &#10003;      |
|                         | message_id           | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| endpoint-authentication | user_ou              | Default |      |           | &#10003;      |
|                         | os                   | Default |      |           | &#10003;      |
|                         | bytes_in             | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | src_port             | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | protocol             | Default |      |           | &#10003;      |
|                         | bytes_out            | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | company              | Default |      |           | &#10003;      |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | department           | Default |      |           | &#10003;      |
|                         | dest_port            | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| endpoint-login          | user_ou              | Default |      |           | &#10003;      |
|                         | os                   | Default |      |           | &#10003;      |
|                         | bytes_in             | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | src_port             | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | protocol             | Default |      |           | &#10003;      |
|                         | bytes_out            | Default |      |           | &#10003;      |
|                         | additional_info      | Default |      |           | &#10003;      |
|                         | process_name         | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | company              | Default |      |           | &#10003;      |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | department           | Default |      |           | &#10003;      |
|                         | dest_port            | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| http-session            | os                   | Default |      |           | &#10003;      |
|                         | service_name         | Default |      |           | &#10003;      |
|                         | interface_name       | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | rule_id              | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | protocol             | Default |      |           | &#10003;      |
|                         | full_name            | Default |      |           | &#10003;      |
|                         | additional_info      | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| network-session         | user_ou              | Default |      |           | &#10003;      |
|                         | src_interface        | Default |      |           | &#10003;      |
|                         | os                   | Default |      |           | &#10003;      |
|                         | bytes_in             | Default |      |           | &#10003;      |
|                         | alert_severity       | Default |      |           | &#10003;      |
|                         | interface_name       | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | users                | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | rule_id              | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | bytes_out            | Default |      |           | &#10003;      |
|                         | app_protocol         | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | dest_host            | Default |      | &#10003;  |               |
|                         | company              | Default |      |           | &#10003;      |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | department           | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | policy               | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
| network-traffic         | peer_gateway         | Default |      |           | &#10003;      |
|                         | interface_name       | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | rule_uid             | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | result               | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | service_id           | Default |      |           | &#10003;      |
|                         | app_protocol         | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | policy               | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
|                         | inzone               | Default |      |           | &#10003;      |
|                         | outzone              | Default |      |           | &#10003;      |
|                         | community            | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | users                | Default |      |           | &#10003;      |
|                         | rule_id              | Default |      |           | &#10003;      |
|                         | additional_info      | Default |      |           | &#10003;      |
|                         | log_uid              | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | dest_host            | Default |      | &#10003;  |               |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
| vpn-login               | src_interface        | Default |      |           | &#10003;      |
|                         | bytes_in             | Default |      |           | &#10003;      |
|                         | alert_severity       | Default |      |           | &#10003;      |
|                         | interface_name       | Default |      |           | &#10003;      |
|                         | rule                 | Default |      |           | &#10003;      |
|                         | dest_translated_ip   | Default |      |           | &#10003;      |
|                         | src_translated_ip    | Default |      |           | &#10003;      |
|                         | protocol             | Default |      |           | &#10003;      |
|                         | app_protocol         | Default |      |           | &#10003;      |
|                         | action               | Default |      |           | &#10003;      |
|                         | company              | Default |      |           | &#10003;      |
|                         | department           | Default |      |           | &#10003;      |
|                         | dest_port            | Default |      |           | &#10003;      |
|                         | origin_name          | Default |      |           | &#10003;      |
|                         | tunnel_protocol      | Default |      |           | &#10003;      |
|                         | policy               | Default |      |           | &#10003;      |
|                         | direction            | Default |      |           | &#10003;      |
|                         | user_ou              | Default |      |           | &#10003;      |
|                         | os                   | Default |      |           | &#10003;      |
|                         | product_name         | Default |      |           | &#10003;      |
|                         | rule_id              | Default |      |           | &#10003;      |
|                         | src_port             | Default |      |           | &#10003;      |
|                         | auth_method          | Default |      |           | &#10003;      |
|                         | bytes_out            | Default |      |           | &#10003;      |
|                         | dest_translated_port | Default |      |           | &#10003;      |
|                         | dest_host            | Default |      | &#10003;  |               |
|                         | src_translated_port  | Default |      |           | &#10003;      |
|                         | origin_ip            | Default |      |           | &#10003;      |
| vpn-logout              | user_ou              |         |      |           | &#10003;      |
|                         | os                   |         |      | &#10003;  |               |
|                         | bytes_in             |         |      | &#10003;  |               |
|                         | rule                 |         |      | &#10003;  |               |
|                         | product_name         |         |      |           | &#10003;      |
|                         | dest_translated_ip   |         |      | &#10003;  |               |
|                         | src_port             |         |      | &#10003;  |               |
|                         | src_translated_ip    |         |      | &#10003;  |               |
|                         | protocol             |         |      | &#10003;  |               |
|                         | bytes_out            | Legacy  |      | &#10003;  |               |
|                         | action               |         |      | &#10003;  |               |
|                         | dest_translated_port |         |      | &#10003;  |               |
|                         | dest_host            | Legacy  |      |           | &#10003;      |
|                         | company              |         |      | &#10003;  |               |
|                         | src_translated_port  |         |      | &#10003;  |               |
|                         | department           |         |      | &#10003;  |               |
|                         | dest_port            |         |      | &#10003;  |               |
|                         | origin_ip            |         |      | &#10003;  |               |
|                         | origin_name          |         |      | &#10003;  |               |
|                         | direction            |         |      | &#10003;  |               |

