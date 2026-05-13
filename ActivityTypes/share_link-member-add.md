share_link-member-add
=====================

Description
-----------
A shared link member was added to a shared link that was sent to a user

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | share_link            |
| Activity      | member-add            |
| Activity Type | share_link-member-add |
| Pretty Name   | Share_link Member Add |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#share_link-member-addsuccess) or a [fail](#share_link-member-addfail).


share_link-member-add:success
-----------------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

share_link-member-add:fail
--------------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| failure_code     |      | &#10003;  |               |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| failure_reason   |      | &#10003;  |               |
| user             |      |           | &#10003;      |