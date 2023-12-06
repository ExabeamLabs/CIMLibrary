call-send
=========

Description
-----------
A user has called another user

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | call      |
| Activity      | send      |
| Activity Type | call-send |
| Pretty Name   | Call Send |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#call-sendsuccess) or a [fail](#call-sendfail).


call-send:success
-----------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| local_user_name |      |           |               |

call-send:fail
--------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |