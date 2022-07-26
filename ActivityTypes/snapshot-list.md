snapshot-list
=============

Description
-----------
An enumeration of snapshot resources took place

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | snapshot      |
| Activity      | list          |
| Activity Type | snapshot-list |
| Pretty Name   | Snapshot List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#snapshot-listsuccess) or a [fail](#snapshot-listfail).


snapshot-list:success
---------------------

There are no fields for this activity type.


snapshot-list:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |