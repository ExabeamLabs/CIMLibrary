role-policy-attach
==================

Description
-----------
A policy document was attached to the role identity

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | role               |
| Activity      | policy-attach      |
| Activity Type | role-policy-attach |
| Pretty Name   | Role Policy Attach |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-policy-attachsuccess) or a [fail](#role-policy-attachfail).


role-policy-attach:success
--------------------------

There are no fields for this activity type.


role-policy-attach:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |