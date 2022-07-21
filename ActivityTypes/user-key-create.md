user-key-create
===============

Description
-----------
A user security key was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-key-createsuccess) or a [fail](#user-key-createfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | user            |
| Activity      | key-create      |
| Activity Type | user-key-create |
| Pretty Name   | User Key Create |
| Legacy Name   |                 |

user-key-create:success
-----------------------

There are no fields for this activity type.


user-key-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |