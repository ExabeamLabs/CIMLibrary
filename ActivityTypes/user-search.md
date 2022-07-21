user-search
===========

Description
-----------
A search was performed on user accounts

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-searchsuccess) or a [fail](#user-searchfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | search      |
| Activity Type | user-search |
| Pretty Name   | User Search |
| Legacy Name   |             |

user-search:success
-------------------

There are no fields for this activity type.


user-search:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |