user-permission-modify
======================

Description
-----------
The permissions of a user were changed

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | user                   |
| Activity      | permission-modify      |
| Activity Type | user-permission-modify |
| Pretty Name   | User Permission Modify |

Legacy Names
------------
| Success | Fail   |
| ------- | ------ |
| NA<br>  | NA<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-permission-modifysuccess) or a [fail](#user-permission-modifyfail).


user-permission-modify:success
------------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| permissions |      |           | &#10003;      |

user-permission-modify:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| permissions    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |