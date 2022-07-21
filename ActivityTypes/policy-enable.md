policy-enable
=============

Description
-----------
The enforcement status of a security policy was changed to enabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-enablesuccess) or a [fail](#policy-enablefail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | policy        |
| Activity      | enable        |
| Activity Type | policy-enable |
| Pretty Name   | Policy Enable |
| Legacy Name   |               |

policy-enable:success
---------------------

There are no fields for this activity type.


policy-enable:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |