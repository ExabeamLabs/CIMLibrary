app-time-modify
===============

Description
-----------
The internal time of the application was updated

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | app             |
| Activity      | time-modify     |
| Activity Type | app-time-modify |
| Pretty Name   | App Time Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-time-modifysuccess) or a [fail](#app-time-modifyfail).


app-time-modify:success
-----------------------

There are no fields for this activity type.


app-time-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |