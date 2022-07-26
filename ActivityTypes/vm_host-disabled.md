vm_host-disabled
================

Description
-----------
The usage configuration of a VM host was set to disabled

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | vm_host          |
| Activity      | disabled         |
| Activity Type | vm_host-disabled |
| Pretty Name   | Vm_host Disabled |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_host-disabledsuccess) or a [fail](#vm_host-disabledfail).


vm_host-disabled:success
------------------------

There are no fields for this activity type.


vm_host-disabled:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |