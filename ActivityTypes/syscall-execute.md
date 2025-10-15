syscall-execute
===============

Description
-----------
Syscall commands were executed on the system

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | syscall         |
| Activity      | execute         |
| Activity Type | syscall-execute |
| Pretty Name   | Syscall Execute |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#syscall-executesuccess) or a [fail](#syscall-executefail).


syscall-execute:success
-----------------------

| Field               | Core | Detection | Informational |
| ------------------- | ---- | --------- | ------------- |
| system_architecture |      |           | &#10003;      |
| syscall_number      |      |           | &#10003;      |
| syscall_name        |      |           | &#10003;      |

syscall-execute:fail
--------------------

| Field               | Core | Detection | Informational |
| ------------------- | ---- | --------- | ------------- |
| system_architecture |      |           | &#10003;      |
| syscall_number      |      |           | &#10003;      |
| syscall_name        |      |           | &#10003;      |