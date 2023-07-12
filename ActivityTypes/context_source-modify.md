context_source-modify
=====================

Description
-----------
Context source was Modified

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | context_source        |
| Activity      | modify                |
| Activity Type | context_source-modify |
| Pretty Name   | Context Source Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_source-modifysuccess) or a [fail](#context_source-modifyfail).


context_source-modify:success
-----------------------------

There are no fields for this activity type.


context_source-modify:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |