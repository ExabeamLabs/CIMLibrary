ds_object-modify
================

Description
-----------
A directory service object was modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ds_object        |
| Activity      | modify           |
| Activity Type | ds_object-modify |
| Pretty Name   | Ds_object Modify |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| ds-access<br> | failed-ds-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-modifysuccess) or a [fail](#ds_object-modifyfail).


ds_object-modify:success
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| event_locality |      |           | &#10003;      |
| object_type    |      |           | &#10003;      |

ds_object-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| object_type    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |