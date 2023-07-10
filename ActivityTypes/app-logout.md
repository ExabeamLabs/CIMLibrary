app-logout
==========

Description
-----------
A user logged out of an application

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | app        |
| Activity      | logout     |
| Activity Type | app-logout |
| Pretty Name   | App Logout |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-logoutsuccess) or a [fail](#app-logoutfail).


app-logout:success
------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| local_user_name |          |           |               |
| user            | &#10003; |           |               |

app-logout:fail
---------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| failure_code    |          | &#10003;  |               |
| local_user_name |          |           |               |
| failure_reason  |          | &#10003;  |               |
| user            | &#10003; |           |               |