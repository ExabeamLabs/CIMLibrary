repository-read
===============

Description
-----------
A git repository read

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | repository      |
| Activity      | read            |
| Activity Type | repository-read |
| Pretty Name   | Repository Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-readsuccess) or a [fail](#repository-readfail).


repository-read:success
-----------------------

There are no fields for this activity type.


repository-read:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |