handle-copy
===========

Description
-----------
A windows handle was copied

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | handle      |
| Activity      | copy        |
| Activity Type | handle-copy |
| Pretty Name   | Handle Copy |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#handle-copysuccess) or a [fail](#handle-copyfail).


handle-copy:success
-------------------

There are no fields for this activity type.


handle-copy:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |