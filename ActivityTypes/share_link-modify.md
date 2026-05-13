share_link-modify
=================

Description
-----------
A shared link that was sent to a user was modified

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | share_link        |
| Activity      | modify            |
| Activity Type | share_link-modify |
| Pretty Name   | Share_link Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#share_link-modifysuccess) or a [fail](#share_link-modifyfail).


share_link-modify:success
-------------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

share_link-modify:fail
----------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| failure_code     |      | &#10003;  |               |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| failure_reason   |      | &#10003;  |               |
| user             |      |           | &#10003;      |