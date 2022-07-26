endpoint-key-create
===================

Description
-----------
An endpoint security key was created

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | endpoint            |
| Activity      | key-create          |
| Activity Type | endpoint-key-create |
| Pretty Name   | Endpoint Key Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-key-createsuccess) or a [fail](#endpoint-key-createfail).


endpoint-key-create:success
---------------------------

There are no fields for this activity type.


endpoint-key-create:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |