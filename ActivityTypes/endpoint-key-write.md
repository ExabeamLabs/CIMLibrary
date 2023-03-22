endpoint-key-write
==================

Description
-----------
An endpoint security key was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | endpoint           |
| Activity      | key-write          |
| Activity Type | endpoint-key-write |
| Pretty Name   | Endpoint Key Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-key-writesuccess) or a [fail](#endpoint-key-writefail).


endpoint-key-write:success
--------------------------

There are no fields for this activity type.


endpoint-key-write:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |