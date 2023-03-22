configuration-create
====================

Description
-----------
A global configuration definition was created

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | configuration        |
| Activity      | create               |
| Activity Type | configuration-create |
| Pretty Name   | Configuration Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-createsuccess) or a [fail](#configuration-createfail).


configuration-create:success
----------------------------

There are no fields for this activity type.


configuration-create:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |