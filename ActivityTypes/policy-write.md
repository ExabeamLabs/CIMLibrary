policy-write
============

Description
-----------
A policy document was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | policy       |
| Activity      | write        |
| Activity Type | policy-write |
| Pretty Name   | Policy Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-writesuccess) or a [fail](#policy-writefail).


policy-write:success
--------------------

There are no fields for this activity type.


policy-write:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |