user-token-create
=================

Description
-----------
A user switched into another user account

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-token-createsuccess) or a [fail](#user-token-createfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | user              |
| Activity      | token-create      |
| Activity Type | user-token-create |
| Pretty Name   | User Token Create |
| Legacy Name   |                   |

user-token-create:success
-------------------------

There are no fields for this activity type.


user-token-create:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |