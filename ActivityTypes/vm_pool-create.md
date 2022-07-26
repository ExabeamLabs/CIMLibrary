vm_pool-create
==============

Description
-----------
A VM pool was created

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_pool        |
| Activity      | create         |
| Activity Type | vm_pool-create |
| Pretty Name   | Vm_pool Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_pool-createsuccess) or a [fail](#vm_pool-createfail).


vm_pool-create:success
----------------------

There are no fields for this activity type.


vm_pool-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |