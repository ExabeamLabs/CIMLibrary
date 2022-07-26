http-response
=============

Description
-----------
A web response was provided from a destination using the HTTP protocol

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | http          |
| Activity      | response      |
| Activity Type | http-response |
| Pretty Name   | Http Response |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#http-responsesuccess) or a [fail](#http-responsefail).


http-response:success
---------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| referrer   |      |           | &#10003;      |
| method     |      | &#10003;  |               |
| mime       |      | &#10003;  |               |
| action     |      |           | &#10003;      |
| category   |      | &#10003;  |               |
| user_agent |      |           | &#10003;      |

http-response:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| referrer       |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| method         |      | &#10003;  |               |
| mime           |      | &#10003;  |               |
| action         |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |
| category       |      | &#10003;  |               |
| user_agent     |      |           | &#10003;      |