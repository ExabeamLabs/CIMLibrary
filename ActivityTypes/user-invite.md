user-invite
===========

Description
-----------
A user account was invited to a workspace

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | invite      |
| Activity Type | user-invite |
| Pretty Name   | User Invite |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-invitesuccess) or a [fail](#user-invitefail).


user-invite:success
-------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_domain |      | &#10003;  |               |
| recipients        |      | &#10003;  |               |
| email_domain      |      | &#10003;  |               |

user-invite:fail
----------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_domain |      | &#10003;  |               |
| failure_code      |      | &#10003;  |               |
| recipients        |      | &#10003;  |               |
| email_domain      |      | &#10003;  |               |
| failure_reason    |      | &#10003;  |               |