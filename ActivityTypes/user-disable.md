user-disable
============

Description
-----------
A user account was disabled

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | user         |
| Activity      | disable      |
| Activity Type | user-disable |
| Pretty Name   | User Disable |

Legacy Names
------------
| Success              | Fail                 |
| -------------------- | -------------------- |
| account-disabled<br> | account-disabled<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-disablesuccess) or a [fail](#user-disablefail).


user-disable:success
--------------------

There are no fields for this activity type.


user-disable:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |