bucket-policy-modify
====================

Description
-----------
The security policy linked to the bucket was updated

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | bucket               |
| Activity      | policy-modify        |
| Activity Type | bucket-policy-modify |
| Pretty Name   | Bucket Policy Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-policy-modifysuccess) or a [fail](#bucket-policy-modifyfail).


bucket-policy-modify:success
----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |

bucket-policy-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |