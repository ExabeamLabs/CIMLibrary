file-unshare
============

Description
-----------
A share of a file was disabled

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | file         |
| Activity      | unshare      |
| Activity Type | file-unshare |
| Pretty Name   | File Unshare |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-unsharesuccess) or a [fail](#file-unsharefail).


file-unshare:success
--------------------

There are no fields for this activity type.


file-unshare:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |