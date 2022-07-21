user-lock
=========

Description
-----------
A user account was locked

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-locksuccess) or a [fail](#user-lockfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | user      |
| Activity      | lock      |
| Activity Type | user-lock |
| Pretty Name   | User Lock |
| Legacy Name   |           |

user-lock:success
-----------------

There are no fields for this activity type.


user-lock:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |