driver-load
===========

Description
-----------
A driver object was loaded into the systems' kernel

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | driver      |
| Activity      | load        |
| Activity Type | driver-load |
| Pretty Name   | Driver Load |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#driver-loadsuccess) or a [fail](#driver-loadfail).


driver-load:success
-------------------

There are no fields for this activity type.


driver-load:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |