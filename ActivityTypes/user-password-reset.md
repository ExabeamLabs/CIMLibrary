user-password-reset
===================

Description
-----------
A user accounts' password was reset

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | user                |
| Activity      | password-reset      |
| Activity Type | user-password-reset |
| Pretty Name   | User Password Reset |

Legacy Names
------------
| Success                    | Fail                       |
| -------------------------- | -------------------------- |
| account-password-reset<br> | account-password-reset<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-resetsuccess) or a [fail](#user-password-resetfail).


user-password-reset:success
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| event_locality |      |           | &#10003;      |

user-password-reset:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| event_locality |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |