group-read
==========

Description
-----------
A request was made to read the content of a group

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | group      |
| Activity      | read       |
| Activity Type | group-read |
| Pretty Name   | Group Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-readsuccess) or a [fail](#group-readfail).


group-read:success
------------------

There are no fields for this activity type.


group-read:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |