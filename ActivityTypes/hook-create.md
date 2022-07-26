hook-create
===========

Description
-----------
A hook object was created

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | hook        |
| Activity      | create      |
| Activity Type | hook-create |
| Pretty Name   | Hook Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#hook-createsuccess) or a [fail](#hook-createfail).


hook-create:success
-------------------

There are no fields for this activity type.


hook-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |