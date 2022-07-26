disk-write
==========

Description
-----------
A disk volume object was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | disk       |
| Activity      | write      |
| Activity Type | disk-write |
| Pretty Name   | Disk Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-writesuccess) or a [fail](#disk-writefail).


disk-write:success
------------------

There are no fields for this activity type.


disk-write:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |