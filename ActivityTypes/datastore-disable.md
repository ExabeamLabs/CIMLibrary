datastore-disable
=================

Description
-----------
The status of a virtualization datastore was set to disable

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | datastore         |
| Activity      | disable           |
| Activity Type | datastore-disable |
| Pretty Name   | Datastore Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-disablesuccess) or a [fail](#datastore-disablefail).


datastore-disable:success
-------------------------

There are no fields for this activity type.


datastore-disable:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |