certificate-validate
====================

Description
-----------
The authenticity of a digital certificate was validated

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | certificate          |
| Activity      | validate             |
| Activity Type | certificate-validate |
| Pretty Name   | Certificate Validate |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-validatesuccess) or a [fail](#certificate-validatefail).


certificate-validate:success
----------------------------

There are no fields for this activity type.


certificate-validate:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |