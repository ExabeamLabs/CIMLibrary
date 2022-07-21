user-password-delete
====================

Description
-----------
A user accounts' password was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-deletesuccess) or a [fail](#user-password-deletefail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-delete      |
| Activity Type | user-password-delete |
| Pretty Name   | User Password Delete |
| Legacy Name   |                      |

user-password-delete:success
----------------------------

There are no fields for this activity type.


user-password-delete:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |