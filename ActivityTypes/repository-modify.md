repository-modify
=================

Description
-----------
The properties or configuration of a git repository were modified

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | repository        |
| Activity      | modify            |
| Activity Type | repository-modify |
| Pretty Name   | Repository Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-modifysuccess) or a [fail](#repository-modifyfail).


repository-modify:success
-------------------------

There are no fields for this activity type.


repository-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |