vm_template-delete
==================

Description
-----------
A VM template was deleted

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | vm_template        |
| Activity      | delete             |
| Activity Type | vm_template-delete |
| Pretty Name   | Vm_template Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_template-deletesuccess) or a [fail](#vm_template-deletefail).


vm_template-delete:success
--------------------------

There are no fields for this activity type.


vm_template-delete:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |