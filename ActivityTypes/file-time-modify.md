file-time-modify
================

Description
-----------
The time properties of a file were modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | file             |
| Activity      | time-modify      |
| Activity Type | file-time-modify |
| Pretty Name   | File Time Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-time-modifysuccess) or a [fail](#file-time-modifyfail).


file-time-modify:success
------------------------

There are no fields for this activity type.


file-time-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |