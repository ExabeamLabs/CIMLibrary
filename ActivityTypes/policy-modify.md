policy-modify
=============

Description
-----------
The content of a security policy document was changed

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | policy        |
| Activity      | modify        |
| Activity Type | policy-modify |
| Pretty Name   | Policy Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-modifysuccess) or a [fail](#policy-modifyfail).


policy-modify:success
---------------------

There are no fields for this activity type.


policy-modify:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |