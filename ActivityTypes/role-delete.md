role-delete
===========

Description
-----------
A security role was deleted

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | role        |
| Activity      | delete      |
| Activity Type | role-delete |
| Pretty Name   | Role Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-deletesuccess) or a [fail](#role-deletefail).


role-delete:success
-------------------

There are no fields for this activity type.


role-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |