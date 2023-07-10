netskope security cloud
=======================

Expression
----------

product = "netskope security cloud"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field             | Status  | Core     | Detection | Informational |
| ---------------------- | ----------------- | ------- | -------- | --------- | ------------- |
| alert-trigger          | site_at           |         |          |           |               |
|                        | file_path         | Legacy  |          |           | &#10003;      |
|                        | additional_info   |         |          |           |               |
|                        | bytes             | Legacy  |          | &#10003;  |               |
|                        | alert_id          | Legacy  |          |           | &#10003;      |
|                        | dest_ip           | Legacy  | &#10003; | &#10003;  |               |
|                        | from_user_at      |         |          |           |               |
|                        | hash_md5          |         |          |           |               |
|                        | file_path_at      |         |          |           |               |
|                        | user              | Legacy  |          | &#10003;  |               |
|                        | shared_with_at    |         |          |           |               |
|                        | target            |         |          |           |               |
| app-activity           | country           | Default |          |           | &#10003;      |
|                        | app_type          | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | src_translated_ip | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | dest_port         | Default |          |           | &#10003;      |
|                        | user_agent        | Default |          |           | &#10003;      |
|                        | os                | Default |          |           | &#10003;      |
|                        | resource          | Default |          |           | &#10003;      |
|                        | file_name         | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | account_user_name |         |          |           |               |
|                        | auth_method       | Default |          |           | &#10003;      |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | additional_info   | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | dest_ip           | Default |          | &#10003;  |               |
|                        | dest_host         | Default |          | &#10003;  |               |
|                        | location          | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | account           | Default |          | &#10003;  |               |
|                        | object            | Default |          |           | &#10003;      |
| app-login              | os                | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | auth_method       | Default |          |           | &#10003;      |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | dest_ip           | Default |          | &#10003;  |               |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | dest_port         | Default |          |           | &#10003;      |
|                        | user_agent        | Default |          |           | &#10003;      |
|                        | object            | Default |          |           | &#10003;      |
| email-receive          | src_ip            | Default |          | &#10003;  |               |
|                        | os                | Default |          |           | &#10003;      |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | operation         | Default |          |           | &#10003;      |
|                        | dest_port         | Default |          |           | &#10003;      |
|                        | url               | Default |          |           | &#10003;      |
| email-send             | os                | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | dest_port         | Default |          |           | &#10003;      |
|                        | user_agent        | Default |          |           | &#10003;      |
| file-copy              | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| file-delete            | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Legacy  |          | &#10003;  |               |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             |         |          |           |               |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| file-download          | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Legacy  |          |           | &#10003;      |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             | Legacy  |          | &#10003;  |               |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| file-list              | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| file-move              | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | file_type         | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| file-permission-modify | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          |         |          |           |               |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             |         |          |           |               |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| file-read              | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Legacy  |          | &#10003;  |               |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             | Legacy  |          |           | &#10003;      |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| file-upload            | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Legacy  |          |           | &#10003;      |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             |         |          |           |               |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| file-write             | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          |         |          |           |               |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | auth_method       |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             | Legacy  |          | &#10003;  |               |
|                        | file_type         | Legacy  |          |           | &#10003;      |
|                        | domain            |         |          |           |               |
|                        | browser           |         |          |           |               |
|                        | action            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | operation         |         |          |           |               |
|                        | dest_port         |         |          |           |               |
|                        | user_agent        |         |          |           |               |
|                        | object            |         |          |           |               |
| group-member-list      | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| group-member-remove    | os                |         |          |           |               |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Legacy  |          | &#10003;  |               |
|                        | url               |         |          |           |               |
|                        | src_ip            |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             |         |          |           |               |
|                        | browser           |         |          |           |               |
|                        | domain            | Legacy  |          |           | &#10003;      |
|                        | action            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | operation         |         |          |           |               |
|                        | user              | Legacy  | &#10003; | &#10003;  |               |
|                        | dest_port         |         |          |           |               |
| http-session           | src_location      | Default |          |           | &#10003;      |
|                        | os                | Default |          |           | &#10003;      |
|                        | src_country       | Default |          |           | &#10003;      |
|                        | additional_info   | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
| log-search             | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| message-send           | src_ip            | Default |          | &#10003;  |               |
|                        | os                | Default |          |           | &#10003;      |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | operation         | Default |          |           | &#10003;      |
|                        | dest_port         | Default |          |           | &#10003;      |
|                        | url               | Default |          |           | &#10003;      |
| network-session        | src_translated_ip | Default |          |           | &#10003;      |
|                        | country_code      | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | location_city     | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | category          | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | user_agent        | Default |          |           | &#10003;      |
| user-create            | src_ip            |         |          |           |               |
|                        | os                |         |          |           |               |
|                        | web_domain        |         |          |           |               |
|                        | bytes             |         |          |           |               |
|                        | browser           |         |          |           |               |
|                        | action            |         |          |           |               |
|                        | location          |         |          |           |               |
|                        | src_host          | Legacy  |          | &#10003;  |               |
|                        | operation         |         |          |           |               |
|                        | dest_port         |         |          |           |               |
|                        | url               |         |          |           |               |
| user-mfa-disable       | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| user-password-delete   | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |
| user-role-modify       | os                | Default |          |           | &#10003;      |
|                        | domain_user_name  |         |          |           |               |
|                        | src_host          | Default |          | &#10003;  |               |
|                        | url               | Default |          |           | &#10003;      |
|                        | src_ip            | Default |          | &#10003;  |               |
|                        | web_domain        | Default |          |           | &#10003;      |
|                        | bytes             | Default |          |           | &#10003;      |
|                        | browser           | Default |          |           | &#10003;      |
|                        | domain            | Default |          |           | &#10003;      |
|                        | action            | Default |          |           | &#10003;      |
|                        | location          | Default |          |           | &#10003;      |
|                        | operation         | Default |          |           | &#10003;      |
|                        | user              | Default |          | &#10003;  |               |
|                        | dest_port         | Default |          |           | &#10003;      |

