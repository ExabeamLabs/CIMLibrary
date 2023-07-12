context_source-create
=====================

Description
-----------
Context source  was created

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | context_source        |
| Activity      | create                |
| Activity Type | context_source-create |
| Pretty Name   | Context Source Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#context_source-createsuccess) or a [fail](#context_source-createfail).


context_source-create:success
-----------------------------

There are no fields for this activity type.


context_source-create:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |