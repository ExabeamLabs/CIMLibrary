user-switch
===========

Description
-----------
A user switched into another user account

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-switchsuccess) or a [fail](#user-switchfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | switch      |
| Activity Type | user-switch |
| Pretty Name   | User Switch |
| Legacy Name   |             |

user-switch:success
-------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          |           | &#10003;      |
| user   | &#10003; | &#10003;  |               |

user-switch:fail
----------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| domain         |          |           | &#10003;      |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |