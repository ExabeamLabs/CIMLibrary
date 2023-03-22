datastore-enable
================

Description
-----------
The status of a virtualization datastore was set to enable

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | datastore        |
| Activity      | enable           |
| Activity Type | datastore-enable |
| Pretty Name   | Datastore Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-enablesuccess) or a [fail](#datastore-enablefail).


datastore-enable:success
------------------------

There are no fields for this activity type.


datastore-enable:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |