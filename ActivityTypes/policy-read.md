policy-read
===========

Description
-----------
The content of a security policy document was read

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | policy      |
| Activity      | read        |
| Activity Type | policy-read |
| Pretty Name   | Policy Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-readsuccess) or a [fail](#policy-readfail).


policy-read:success
-------------------

There are no fields for this activity type.


policy-read:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |