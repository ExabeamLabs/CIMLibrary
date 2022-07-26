disk-read
=========

Description
-----------
The content of a disk\volume object was read

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | disk      |
| Activity      | read      |
| Activity Type | disk-read |
| Pretty Name   | Disk Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-readsuccess) or a [fail](#disk-readfail).


disk-read:success
-----------------

There are no fields for this activity type.


disk-read:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |