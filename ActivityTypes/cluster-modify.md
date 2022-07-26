cluster-modify
==============

Description
-----------
The properties or configuration of a virtualization cluster were modified

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | cluster        |
| Activity      | modify         |
| Activity Type | cluster-modify |
| Pretty Name   | Cluster Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#cluster-modifysuccess) or a [fail](#cluster-modifyfail).


cluster-modify:success
----------------------

There are no fields for this activity type.


cluster-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |