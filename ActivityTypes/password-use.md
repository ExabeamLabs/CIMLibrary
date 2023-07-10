password-use
============

Description
-----------
A stored password was used by a user

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | password     |
| Activity      | use          |
| Activity Type | password-use |
| Pretty Name   | Password Use |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-usesuccess) or a [fail](#password-usefail).


password-use:success
--------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| local_user_name |      |           |               |

password-use:fail
-----------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |