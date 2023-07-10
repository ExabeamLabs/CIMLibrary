app-register
============

Description
-----------
A user has registered to an app

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | app          |
| Activity      | register     |
| Activity Type | app-register |
| Pretty Name   | App Register |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-registersuccess) or a [fail](#app-registerfail).


app-register:success
--------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| local_user_name |          |           |               |
| user            | &#10003; |           |               |

app-register:fail
-----------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| failure_code    |          | &#10003;  |               |
| local_user_name |          |           |               |
| failure_reason  |          | &#10003;  |               |
| user            | &#10003; |           |               |