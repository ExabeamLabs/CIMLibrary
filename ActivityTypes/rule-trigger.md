rule-trigger
============

Description
-----------
A trigger of a security rule was recorded on a security product or program

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | rule         |
| Activity      | trigger      |
| Activity Type | rule-trigger |
| Pretty Name   | Rule Trigger |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-triggersuccess) or a [fail](#rule-triggerfail).


rule-trigger:success
--------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| rule_severity   |      |           | &#10003;      |
| local_user_name |      |           |               |
| rule            |      |           | &#10003;      |
| src_host        |      | &#10003;  |               |
| rule_usecases   |      |           | &#10003;      |
| log_time        |      |           | &#10003;      |
| src_ip          |      | &#10003;  |               |
| trigger_time    |      |           | &#10003;      |
| event_id        |      |           | &#10003;      |
| rule_reason     |      |           | &#10003;      |
| dest_ip         |      | &#10003;  |               |
| dest_host       |      | &#10003;  |               |
| mitre_labels    |      |           | &#10003;      |
| asset_labels    |      |           | &#10003;      |
| user            |      | &#10003;  |               |
| event_time      |      |           | &#10003;      |

rule-trigger:fail
-----------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| rule_severity   |      |           | &#10003;      |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| rule            |      |           | &#10003;      |
| src_host        |      | &#10003;  |               |
| rule_usecases   |      |           | &#10003;      |
| failure_reason  |      | &#10003;  |               |
| log_time        |      |           | &#10003;      |
| src_ip          |      | &#10003;  |               |
| trigger_time    |      |           | &#10003;      |
| event_id        |      |           | &#10003;      |
| rule_reason     |      |           | &#10003;      |
| dest_ip         |      | &#10003;  |               |
| dest_host       |      | &#10003;  |               |
| mitre_labels    |      |           | &#10003;      |
| asset_labels    |      |           | &#10003;      |
| user            |      | &#10003;  |               |
| event_time      |      |           | &#10003;      |