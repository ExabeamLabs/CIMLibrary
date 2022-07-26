file-stream-create
==================

Description
-----------
A file stream (windows) was created

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | file               |
| Activity      | stream-create      |
| Activity Type | file-stream-create |
| Pretty Name   | File Stream Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-stream-createsuccess) or a [fail](#file-stream-createfail).


file-stream-create:success
--------------------------

There are no fields for this activity type.


file-stream-create:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |