secret-read
===========

Description
-----------
The content of a secret credentials object was read

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | secret      |
| Activity      | read        |
| Activity Type | secret-read |
| Pretty Name   | Secret Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-readsuccess) or a [fail](#secret-readfail).


secret-read:success
-------------------

There are no fields for this activity type.


secret-read:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |