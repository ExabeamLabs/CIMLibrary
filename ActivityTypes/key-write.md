key-write
=========

Description
-----------
A global security key object was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | key       |
| Activity      | write     |
| Activity Type | key-write |
| Pretty Name   | Key Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#key-writesuccess) or a [fail](#key-writefail).


key-write:success
-----------------

There are no fields for this activity type.


key-write:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |