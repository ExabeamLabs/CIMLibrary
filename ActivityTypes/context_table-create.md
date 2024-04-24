context_table-create
====================

Description
-----------
Context table  was created

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | context_table        |
| Activity      | create               |
| Activity Type | context_table-create |
| Pretty Name   | Context Table Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_table-createsuccess) or a [fail](#context_table-createfail).


context_table-create:success
----------------------------

There are no fields for this activity type.


context_table-create:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |