user-unlock
===========

Description
-----------
A user account was unlocked

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | unlock      |
| Activity Type | user-unlock |
| Pretty Name   | User Unlock |

Legacy Names
------------
| Success              | Fail                 |
| -------------------- | -------------------- |
| account-unlocked<br> | account-unlocked<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-unlocksuccess) or a [fail](#user-unlockfail).


user-unlock:success
-------------------

There are no fields for this activity type.


user-unlock:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |