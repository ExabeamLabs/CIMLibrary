user-delete
===========

Description
-----------
A user account was deleted

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | delete      |
| Activity Type | user-delete |
| Pretty Name   | User Delete |

Legacy Names
------------
| Success             | Fail                |
| ------------------- | ------------------- |
| account-deleted<br> | account-deleted<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-deletesuccess) or a [fail](#user-deletefail).


user-delete:success
-------------------

There are no fields for this activity type.


user-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |