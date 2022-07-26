file-permission-read
====================

Description
-----------
A request was made to read the permissions of a file

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | file                 |
| Activity      | permission-read      |
| Activity Type | file-permission-read |
| Pretty Name   | File Permission Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-permission-readsuccess) or a [fail](#file-permission-readfail).


file-permission-read:success
----------------------------

There are no fields for this activity type.


file-permission-read:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |