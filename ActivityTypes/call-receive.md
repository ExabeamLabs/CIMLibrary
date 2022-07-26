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

There are no fields for this activity type.


call-receive:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |