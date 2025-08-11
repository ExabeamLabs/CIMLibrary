user-password-modify
====================

Description
-----------
A user accounts' password was changed

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-modify      |
| Activity Type | user-password-modify |
| Pretty Name   | User Password Modify |

Legacy Names
------------
| Success                     | Fail                               |
| --------------------------- | ---------------------------------- |
| account-password-change<br> | account-password-change-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-modifysuccess) or a [fail](#user-password-modifyfail).


user-password-modify:success
----------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| event_locality  |      |           | &#10003;      |
| local_user_name |      |           |               |
| user            |      | &#10003;  |               |

user-password-modify:fail
-------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| event_locality  |      |           | &#10003;      |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |
| user            |      | &#10003;  |               |