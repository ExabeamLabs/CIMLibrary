file-restore
============

Description
-----------
A file that was deleted was restored

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | file         |
| Activity      | restore      |
| Activity Type | file-restore |
| Pretty Name   | File Restore |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-restoresuccess) or a [fail](#file-restorefail).


file-restore:success
--------------------

There are no fields for this activity type.


file-restore:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |