vm_pool-modify
==============

Description
-----------
The properties or configuration of a VM pool were modified

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_pool        |
| Activity      | modify         |
| Activity Type | vm_pool-modify |
| Pretty Name   | Vm_pool Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_pool-modifysuccess) or a [fail](#vm_pool-modifyfail).


vm_pool-modify:success
----------------------

There are no fields for this activity type.


vm_pool-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |