vm_host-enable
==============

Description
-----------
The usage configuration of a VM host was set to enabled

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_host        |
| Activity      | enable         |
| Activity Type | vm_host-enable |
| Pretty Name   | Vm_host Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_host-enablesuccess) or a [fail](#vm_host-enablefail).


vm_host-enable:success
----------------------

There are no fields for this activity type.


vm_host-enable:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |