user-invite
===========

Description
-----------
A user account was invited to a workspace

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-invitesuccess) or a [fail](#user-invitefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | invite      |
| Activity Type | user-invite |
| Pretty Name   | User Invite |
| Legacy Name   |             |

user-invite:success
-------------------

There are no fields for this activity type.


user-invite:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |