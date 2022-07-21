user-policy-attach
==================

Description
-----------
A policy document was attached to the user

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-policy-attachsuccess) or a [fail](#user-policy-attachfail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | user               |
| Activity      | policy-attach      |
| Activity Type | user-policy-attach |
| Pretty Name   | User Policy Attach |
| Legacy Name   |                    |

user-policy-attach:success
--------------------------

There are no fields for this activity type.


user-policy-attach:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |