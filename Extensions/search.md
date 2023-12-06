search
======

Expression
----------

product = "search"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field               | Status  | Core     | Detection | Informational |
| ---------------------- | ------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger          | trigger_type        |         |          |           |               |
|                        | local_user_name     |         |          |           |               |
|                        | src_host            | Legacy  | &#10003; | &#10003;  |               |
|                        | rule_usecases       |         |          |           | &#10003;      |
|                        | original_risk_score |         |          |           |               |
|                        | log_time            |         |          |           |               |
|                        | base_risk_score     |         |          |           |               |
|                        | event_id            |         |          |           | &#10003;      |
|                        | trigger_entity      |         |          |           |               |
|                        | dest_host           | Legacy  |          | &#10003;  |               |
|                        | mitre_labels        |         |          |           | &#10003;      |
|                        | alert_reason        |         |          |           | &#10003;      |
|                        | asset_labels        |         |          |           | &#10003;      |
|                        | user                | Legacy  |          | &#10003;  |               |
|                        | event_time          |         |          |           | &#10003;      |
| app-activity           | src_ip              | Default |          | &#10003;  |               |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
| app-login              | src_ip              | Default |          | &#10003;  |               |
|                        | additional_info     | Default |          |           | &#10003;      |
| app-notification       | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |
| group-modify           | src_ip              |         |          |           |               |
|                        | app                 |         |          |           |               |
|                        | additional_info     |         |          |           |               |
|                        | domain              | Legacy  |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Legacy  | &#10003; |           |               |
|                        | operation           |         |          |           |               |
| log_source-add         | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |
| log_source-modify      | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |
| role-delete            | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |
| role-permission-modify | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |
| rule-create            | src_ip              | Default |          | &#10003;  |               |
|                        | app                 | Default |          |           | &#10003;      |
|                        | additional_info     | Default |          |           | &#10003;      |
|                        | domain              | Default |          |           | &#10003;      |
|                        | domain_user_name    |         |          |           |               |
|                        | user                | Default |          | &#10003;  |               |
|                        | operation           | Default |          |           | &#10003;      |

