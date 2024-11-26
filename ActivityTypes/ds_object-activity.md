ds_object-activity
==================

Description
-----------
An activity on a directory service object

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | ds_object          |
| Activity      | activity           |
| Activity Type | ds_object-activity |
| Pretty Name   | Ds_object Activity |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| ds-access<br> | failed-ds-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-activitysuccess) or a [fail](#ds_object-activityfail).


ds_object-activity:success
--------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| object_type |      |           | &#10003;      |

ds_object-activity:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| object_type    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |