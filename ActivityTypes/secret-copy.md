secret-copy
===========

Description
-----------
A secret credentials object was copied

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | secret      |
| Activity      | copy        |
| Activity Type | secret-copy |
| Pretty Name   | Secret Copy |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-copysuccess) or a [fail](#secret-copyfail).


secret-copy:success
-------------------

There are no fields for this activity type.


secret-copy:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |