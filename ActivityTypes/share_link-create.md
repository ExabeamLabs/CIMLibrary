share_link-create
=================

Description
-----------
A shared link that was sent to a user was created

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | share_link        |
| Activity      | create            |
| Activity Type | share_link-create |
| Pretty Name   | Share_link Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#share_link-createsuccess) or a [fail](#share_link-createfail).


share_link-create:success
-------------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

share_link-create:fail
----------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| failure_code     |      | &#10003;  |               |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| failure_reason   |      | &#10003;  |               |
| user             |      |           | &#10003;      |