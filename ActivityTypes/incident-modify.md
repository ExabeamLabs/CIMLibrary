incident-modify
===============

Description
-----------
The properties or content of a security incident were changed on a security product

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | incident        |
| Activity      | modify          |
| Activity Type | incident-modify |
| Pretty Name   | Incident Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#incident-modifysuccess) or a [fail](#incident-modifyfail).


incident-modify:success
-----------------------

There are no fields for this activity type.


incident-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |