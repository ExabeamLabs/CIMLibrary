policy-disable
==============

Description
-----------
The enforcement status of a security policy was changed to disabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-disablesuccess) or a [fail](#policy-disablefail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | policy         |
| Activity      | disable        |
| Activity Type | policy-disable |
| Pretty Name   | Policy Disable |
| Legacy Name   |                |

policy-disable:success
----------------------

There are no fields for this activity type.


policy-disable:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |