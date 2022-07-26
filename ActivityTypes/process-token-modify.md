process-token-modify
====================

Description
-----------
A process token was changed in a process

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | process              |
| Activity      | token-modify         |
| Activity Type | process-token-modify |
| Pretty Name   | Process Token Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-token-modifysuccess) or a [fail](#process-token-modifyfail).


process-token-modify:success
----------------------------

There are no fields for this activity type.


process-token-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |