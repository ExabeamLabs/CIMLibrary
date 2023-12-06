call-receive
============

Description
-----------
A user has recived a call from another user

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | call         |
| Activity      | receive      |
| Activity Type | call-receive |
| Pretty Name   | Call Receive |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#call-receivesuccess) or a [fail](#call-receivefail).


call-receive:success
--------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| local_user_name |      |           |               |

call-receive:fail
-----------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |