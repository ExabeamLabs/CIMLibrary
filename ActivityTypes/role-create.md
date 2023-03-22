role-create
===========

Description
-----------
A security role was created

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | role        |
| Activity      | create      |
| Activity Type | role-create |
| Pretty Name   | Role Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-createsuccess) or a [fail](#role-createfail).


role-create:success
-------------------

There are no fields for this activity type.


role-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |