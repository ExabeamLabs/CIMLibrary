user-name-modify
================

Description
-----------
The name of a user account was modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-name-modifysuccess) or a [fail](#user-name-modifyfail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | name-modify      |
| Activity Type | user-name-modify |
| Pretty Name   | User Name Modify |
| Legacy Name   |                  |

user-name-modify:success
------------------------

There are no fields for this activity type.


user-name-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |