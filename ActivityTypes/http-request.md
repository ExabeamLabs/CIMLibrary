http-request
============

Description
-----------
A web query was made using the HTTP protocol

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | http         |
| Activity      | request      |
| Activity Type | http-request |
| Pretty Name   | Http Request |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#http-requestsuccess) or a [fail](#http-requestfail).


http-request:success
--------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| referrer          |      |           | &#10003;      |
| user_agent_client |      |           |               |
| method            |      | &#10003;  |               |
| mime              |      | &#10003;  |               |
| action            |      |           | &#10003;      |
| category          |      | &#10003;  |               |
| user_agent        |      |           | &#10003;      |

http-request:fail
-----------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| referrer          |      |           | &#10003;      |
| failure_code      |      | &#10003;  |               |
| user_agent_client |      |           |               |
| method            |      | &#10003;  |               |
| mime              |      | &#10003;  |               |
| action            |      |           | &#10003;      |
| failure_reason    |      | &#10003;  |               |
| category          |      | &#10003;  |               |
| user_agent        |      |           | &#10003;      |