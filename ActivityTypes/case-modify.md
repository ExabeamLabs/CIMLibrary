case-modify
===========

Description
-----------
The properties or content of a security incident were changed on a security product

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | case        |
| Activity      | modify      |
| Activity Type | case-modify |
| Pretty Name   | Case Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#case-modifysuccess) or a [fail](#case-modifyfail).


case-modify:success
-------------------

There are no fields for this activity type.


case-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |