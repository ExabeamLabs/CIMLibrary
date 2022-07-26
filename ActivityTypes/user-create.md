user-create
===========

Description
-----------
A user account was created

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | create      |
| Activity Type | user-create |
| Pretty Name   | User Create |

Legacy Names
------------
| Success              | Fail                 |
| -------------------- | -------------------- |
| account-creation<br> | account-creation<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-createsuccess) or a [fail](#user-createfail).


user-create:success
-------------------

There are no fields for this activity type.


user-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |