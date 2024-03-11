script-execute
==============

Description
-----------
Scripting commands were executed on the system

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | script         |
| Activity      | execute        |
| Activity Type | script-execute |
| Pretty Name   | Script Execute |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#script-executesuccess) or a [fail](#script-executefail).


script-execute:success
----------------------

There are no fields for this activity type.


script-execute:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |