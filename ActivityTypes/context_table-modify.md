context_table-modify
====================

Description
-----------
Context table was Modified

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | context_table        |
| Activity      | modify               |
| Activity Type | context_table-modify |
| Pretty Name   | Context Table Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_table-modifysuccess) or a [fail](#context_table-modifyfail).


context_table-modify:success
----------------------------

There are no fields for this activity type.


context_table-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |