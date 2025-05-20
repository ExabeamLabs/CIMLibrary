user-token-modify
=================

Description
-----------
A user token was changed in a process

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | user              |
| Activity      | token-modify      |
| Activity Type | user-token-modify |
| Pretty Name   | User Token Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-token-modifysuccess) or a [fail](#user-token-modifyfail).


user-token-modify:success
-------------------------

There are no fields for this activity type.


user-token-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |