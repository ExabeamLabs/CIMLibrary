user-invite-accept
==================

Description
-----------
A user account invitation to workspace was accepted

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | user               |
| Activity      | invite-accept      |
| Activity Type | user-invite-accept |
| Pretty Name   | User Invite Accept |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-invite-acceptsuccess) or a [fail](#user-invite-acceptfail).


user-invite-accept:success
--------------------------

There are no fields for this activity type.


user-invite-accept:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |