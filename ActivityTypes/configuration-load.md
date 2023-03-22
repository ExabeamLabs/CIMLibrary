configuration-load
==================

Description
-----------
A global configuration definition was loaded into the app, replacing the current definition if it exists

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | configuration      |
| Activity      | load               |
| Activity Type | configuration-load |
| Pretty Name   | Configuration Load |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-loadsuccess) or a [fail](#configuration-loadfail).


configuration-load:success
--------------------------

There are no fields for this activity type.


configuration-load:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |