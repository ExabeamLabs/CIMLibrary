datastore-modify
================

Description
-----------
The properties or configuration of a virtualization datastore were modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | datastore        |
| Activity      | modify           |
| Activity Type | datastore-modify |
| Pretty Name   | Datastore Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-modifysuccess) or a [fail](#datastore-modifyfail).


datastore-modify:success
------------------------

There are no fields for this activity type.


datastore-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |