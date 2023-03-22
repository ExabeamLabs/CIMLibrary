user-invite-cancel
==================

Description
-----------
A user account invitation to workspace was canceled

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | user               |
| Activity      | invite-cancel      |
| Activity Type | user-invite-cancel |
| Pretty Name   | User Invite Cancel |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-invite-cancelsuccess) or a [fail](#user-invite-cancelfail).


user-invite-cancel:success
--------------------------

There are no fields for this activity type.


user-invite-cancel:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |