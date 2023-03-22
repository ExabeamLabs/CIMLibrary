snapshot-create
===============

Description
-----------
A snapshot was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | snapshot        |
| Activity      | create          |
| Activity Type | snapshot-create |
| Pretty Name   | Snapshot Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#snapshot-createsuccess) or a [fail](#snapshot-createfail).


snapshot-create:success
-----------------------

There are no fields for this activity type.


snapshot-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |