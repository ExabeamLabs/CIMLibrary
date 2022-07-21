group-policy-attach
===================

Description
-----------
A policy document was assigned to the group

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-policy-attachsuccess) or a [fail](#group-policy-attachfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | group               |
| Activity      | policy-attach       |
| Activity Type | group-policy-attach |
| Pretty Name   | Group Policy Attach |
| Legacy Name   |                     |

group-policy-attach:success
---------------------------

There are no fields for this activity type.


group-policy-attach:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |