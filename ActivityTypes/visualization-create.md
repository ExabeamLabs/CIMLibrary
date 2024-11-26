visualization-create
====================

Description
-----------
A Visualization was created 

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | visualization         |
| Activity      | create                |
| Activity Type | visualization-create  |
| Pretty Name   | Visualization Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-createsuccess) or a [fail](#visualization-createfail).


visualization-create:success
----------------------------

There are no fields for this activity type.


visualization-create:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |