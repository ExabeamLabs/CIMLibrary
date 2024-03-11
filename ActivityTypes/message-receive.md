message-receive
===============

Description
-----------
A chat messaged was received by a user

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | message         |
| Activity      | receive         |
| Activity Type | message-receive |
| Pretty Name   | Message Receive |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#message-receivesuccess) or a [fail](#message-receivefail).


message-receive:success
-----------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| dest_domain |      |           | &#10003;      |
| dest_user   |      |           | &#10003;      |

message-receive:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| dest_domain    |      |           | &#10003;      |
| dest_user      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |