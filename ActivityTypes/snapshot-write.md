snapshot-write
==============

Description
-----------
A snapshot object was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | snapshot       |
| Activity      | write          |
| Activity Type | snapshot-write |
| Pretty Name   | Snapshot Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#snapshot-writesuccess) or a [fail](#snapshot-writefail).


snapshot-write:success
----------------------

There are no fields for this activity type.


snapshot-write:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |