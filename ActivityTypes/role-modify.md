role-modify
===========

Description
-----------
The properties or configuration of a security role were changed

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | role        |
| Activity      | modify      |
| Activity Type | role-modify |
| Pretty Name   | Role Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-modifysuccess) or a [fail](#role-modifyfail).


role-modify:success
-------------------

There are no fields for this activity type.


role-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |