bucket-policy-read
==================

Description
-----------
The security policy linked to the bucket was read

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | bucket             |
| Activity      | policy-read        |
| Activity Type | bucket-policy-read |
| Pretty Name   | Bucket Policy Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-policy-readsuccess) or a [fail](#bucket-policy-readfail).


bucket-policy-read:success
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |

bucket-policy-read:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |