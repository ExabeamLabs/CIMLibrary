link-create
===========

Description
-----------
A link was created between two endpoint objects

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | link        |
| Activity      | create      |
| Activity Type | link-create |
| Pretty Name   | Link Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#link-createsuccess) or a [fail](#link-createfail).


link-create:success
-------------------

There are no fields for this activity type.


link-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |