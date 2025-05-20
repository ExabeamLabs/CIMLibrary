group-modify
============

Description
-----------
A group was modified

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | group        |
| Activity      | modify       |
| Activity Type | group-modify |
| Pretty Name   | Group Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-modifysuccess) or a [fail](#group-modifyfail).


group-modify:success
--------------------

There are no fields for this activity type.


group-modify:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |