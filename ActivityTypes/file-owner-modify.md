file-owner-modify
=================

Description
-----------
The owner of a file was changed

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | file              |
| Activity      | owner-modify      |
| Activity Type | file-owner-modify |
| Pretty Name   | File Owner Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-owner-modifysuccess) or a [fail](#file-owner-modifyfail).


file-owner-modify:success
-------------------------

There are no fields for this activity type.


file-owner-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |