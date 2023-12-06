user-enable
===========

Description
-----------
A user account was enabled

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | enable      |
| Activity Type | user-enable |
| Pretty Name   | User Enable |

Legacy Names
------------
| Success             | Fail                |
| ------------------- | ------------------- |
| account-enabled<br> | account-enabled<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-enablesuccess) or a [fail](#user-enablefail).


user-enable:success
-------------------

There are no fields for this activity type.


user-enable:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |