context_table-delete
====================

Description
-----------
Context table was deleted

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | context_table        |
| Activity      | delete               |
| Activity Type | context_table-delete |
| Pretty Name   | Context Table Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_table-deletesuccess) or a [fail](#context_table-deletefail).


context_table-delete:success
----------------------------

There are no fields for this activity type.


context_table-delete:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |