user-lock
=========

Description
-----------
A user account was locked

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | user      |
| Activity      | lock      |
| Activity Type | user-lock |
| Pretty Name   | User Lock |

Legacy Names
------------
| Success             | Fail                |
| ------------------- | ------------------- |
| account-lockout<br> | account-lockout<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-locksuccess) or a [fail](#user-lockfail).


user-lock:success
-----------------

There are no fields for this activity type.


user-lock:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |