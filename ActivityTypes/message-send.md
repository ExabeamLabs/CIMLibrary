message-send
============

Description
-----------
A chat message was sent to a user

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | message      |
| Activity      | send         |
| Activity Type | message-send |
| Pretty Name   | Message Send |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#message-sendsuccess) or a [fail](#message-sendfail).


message-send:success
--------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| dest_domain |      |           | &#10003;      |
| dest_user   |      |           | &#10003;      |

message-send:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| dest_domain    |      |           | &#10003;      |
| dest_user      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |