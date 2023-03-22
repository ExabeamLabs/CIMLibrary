datacenter-modify
=================

Description
-----------
The properties or configuration of a virtualization datacenter were modified

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | datacenter        |
| Activity      | modify            |
| Activity Type | datacenter-modify |
| Pretty Name   | Datacenter Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#datacenter-modifysuccess) or a [fail](#datacenter-modifyfail).


datacenter-modify:success
-------------------------

There are no fields for this activity type.


datacenter-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |