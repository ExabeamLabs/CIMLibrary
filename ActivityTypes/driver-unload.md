driver-unload
=============

Description
-----------
A driver object was unloaded from the system's kernel

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | driver        |
| Activity      | unload        |
| Activity Type | driver-unload |
| Pretty Name   | Driver Unload |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#driver-unloadsuccess) or a [fail](#driver-unloadfail).


driver-unload:success
---------------------

There are no fields for this activity type.


driver-unload:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |