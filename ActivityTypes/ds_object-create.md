ds_object-create
================

Description
-----------
A directory service object was created

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ds_object        |
| Activity      | create           |
| Activity Type | ds_object-create |
| Pretty Name   | Ds_object Create |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| ds-access<br> | failed-ds-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-createsuccess) or a [fail](#ds_object-createfail).


ds_object-create:success
------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| object_type |      |           | &#10003;      |

ds_object-create:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| object_type    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |