vm_host-modify
==============

Description
-----------
The properties or configuration of a VM host were changed

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_host        |
| Activity      | modify         |
| Activity Type | vm_host-modify |
| Pretty Name   | Vm_host Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_host-modifysuccess) or a [fail](#vm_host-modifyfail).


vm_host-modify:success
----------------------

There are no fields for this activity type.


vm_host-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |