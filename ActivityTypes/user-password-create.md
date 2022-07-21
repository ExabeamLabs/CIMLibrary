user-password-create
====================

Description
-----------
A password was created for a user account

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-createsuccess) or a [fail](#user-password-createfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-create      |
| Activity Type | user-password-create |
| Pretty Name   | User Password Create |
| Legacy Name   |                      |

user-password-create:success
----------------------------

There are no fields for this activity type.


user-password-create:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |