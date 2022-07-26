endpoint-create
===============

Description
-----------
An endpoint object or instance was create

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | create          |
| Activity Type | endpoint-create |
| Pretty Name   | Endpoint Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-createsuccess) or a [fail](#endpoint-createfail).


endpoint-create:success
-----------------------

There are no fields for this activity type.


endpoint-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |