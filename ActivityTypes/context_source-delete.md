context_source-delete
=====================

Description
-----------
Context source was deleted

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | context_source        |
| Activity      | delete                |
| Activity Type | context_source-delete |
| Pretty Name   | Context Source Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_source-deletesuccess) or a [fail](#context_source-deletefail).


context_source-delete:success
-----------------------------

There are no fields for this activity type.


context_source-delete:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |