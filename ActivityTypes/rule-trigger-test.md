rule-trigger-test
=================

Description
-----------
A test trigger of a security rule was recorded on a security product or program

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | rule              |
| Activity      | trigger-test      |
| Activity Type | rule-trigger-test |
| Pretty Name   | Rule Trigger Test |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-trigger-testsuccess) or a [fail](#rule-trigger-testfail).


rule-trigger-test:success
-------------------------

| Field                  | Core | Detection | Informational |
| ---------------------- | ---- | --------- | ------------- |
| observed_activity      |      |           | &#10003;      |
| event_field            |      |           | &#10003;      |
| local_user_name        |      |           |               |
| rule                   |      |           | &#10003;      |
| technique              |      |           | &#10003;      |
| rules                  |      |           | &#10003;      |
| rule_usecases          |      |           | &#10003;      |
| type                   |      |           | &#10003;      |
| src_local_host         |      | &#10003;  |               |
| tactic                 |      |           | &#10003;      |
| src_ip                 |      | &#10003;  |               |
| subscription_code      |      |           | &#10003;      |
| src_product            |      |           | &#10003;      |
| trigger_time           |      |           | &#10003;      |
| field_value            |      |           | &#10003;      |
| src_vendor             |      |           | &#10003;      |
| dest_local_zone        |      | &#10003;  |               |
| event_filter           |      |           | &#10003;      |
| create_case            |      |           | &#10003;      |
| rule_severity          |      |           | &#10003;      |
| rule_source            |      |           | &#10003;      |
| entity_key             |      |           | &#10003;      |
| recoverability         |      |           | &#10003;      |
| risk_score             |      |           | &#10003;      |
| dest_local_host        |      | &#10003;  |               |
| previous_id            |      |           | &#10003;      |
| event_to_time_millis   |      |           | &#10003;      |
| src_host               |      | &#10003;  |               |
| case_description       |      |           | &#10003;      |
| log_time               |      |           | &#10003;      |
| event_url              |      |           | &#10003;      |
| tactic_key             |      |           | &#10003;      |
| technique_key          |      |           | &#10003;      |
| event_id               |      |           | &#10003;      |
| entity_type            |      |           | &#10003;      |
| rule_reason            |      |           | &#10003;      |
| entities               |      |           | &#10003;      |
| dest_ip                |      | &#10003;  |               |
| local_zone             |      | &#10003;  |               |
| event_from_time_millis |      |           | &#10003;      |
| src_local_zone         |      | &#10003;  |               |
| dest_host              |      | &#10003;  |               |
| local_asset            |      | &#10003;  |               |
| mitre_labels           |      |           | &#10003;      |
| asset_labels           |      |           | &#10003;      |
| user                   |      | &#10003;  |               |
| event_time             |      |           | &#10003;      |

A failure activity is not currently supported for this activity-type.