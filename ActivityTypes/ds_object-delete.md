ds_object-delete
================

Description
-----------
A directory service object was deleted

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ds_object        |
| Activity      | delete           |
| Activity Type | ds_object-delete |
| Pretty Name   | Ds_object Delete |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| ds-access<br> | failed-ds-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-deletesuccess) or a [fail](#ds_object-deletefail).


ds_object-delete:success
------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| object_type |      |           | &#10003;      |

ds_object-delete:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| object_type    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |