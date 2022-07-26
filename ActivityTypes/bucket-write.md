bucket-write
============

Description
-----------
A cloud bucket was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | bucket       |
| Activity      | write        |
| Activity Type | bucket-write |
| Pretty Name   | Bucket Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-writesuccess) or a [fail](#bucket-writefail).


bucket-write:success
--------------------

There are no fields for this activity type.


bucket-write:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |