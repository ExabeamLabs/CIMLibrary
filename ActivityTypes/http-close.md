http-close
==========

Description
-----------
A HTTP session was closed

The possible fields for this activity type will vary depending on whether the activity was a [success](#http-closesuccess) or a [fail](#http-closefail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | http       |
| Activity      | close      |
| Activity Type | http-close |
| Pretty Name   | Http Close |
| Legacy Name   |            |

http-close:success
------------------

There are no fields for this activity type.


http-close:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |