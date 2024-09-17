template-modify
===============

Description
-----------
Template was modified

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | template        |
| Activity      | modify          |
| Activity Type | template-modify |
| Pretty Name   | Template modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#template-modifysuccess) or a [fail](#template-modifyfail).


template-modify:success
-----------------------

There are no fields for this activity type.


template-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |