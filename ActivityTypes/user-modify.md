user-modify
===========

Description
-----------
The attributes of a user were changed

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | modify      |
| Activity Type | user-modify |
| Pretty Name   | User Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-modifysuccess) or a [fail](#user-modifyfail).


user-modify:success
-------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| properties |      |           | &#10003;      |

user-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| properties     |      |           | &#10003;      |