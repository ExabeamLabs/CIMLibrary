bucket-property-read
====================

Description
-----------
The property linked to the bucket was read

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | bucket               |
| Activity      | property-read        |
| Activity Type | bucket-property-read |
| Pretty Name   | Bucket Property Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-property-readsuccess) or a [fail](#bucket-property-readfail).


bucket-property-read:success
----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |

bucket-property-read:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |