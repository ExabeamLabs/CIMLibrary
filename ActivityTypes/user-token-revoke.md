user-token-revoke
=================

Description
-----------
A user token was revoked in a process

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | user              |
| Activity      | token-revoke      |
| Activity Type | user-token-revoke |
| Pretty Name   | User Token Revoke |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-token-revokesuccess) or a [fail](#user-token-revokefail).


user-token-revoke:success
-------------------------

There are no fields for this activity type.


user-token-revoke:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |