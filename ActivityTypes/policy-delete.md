policy-delete
=============

Description
-----------
A security policy document was deleted

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | policy        |
| Activity      | delete        |
| Activity Type | policy-delete |
| Pretty Name   | Policy Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-deletesuccess) or a [fail](#policy-deletefail).


policy-delete:success
---------------------

There are no fields for this activity type.


policy-delete:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |