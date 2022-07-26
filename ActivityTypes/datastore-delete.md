datastore-delete
================

Description
-----------
A virtualization datastore was deleted

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | datastore        |
| Activity      | delete           |
| Activity Type | datastore-delete |
| Pretty Name   | Datastore Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-deletesuccess) or a [fail](#datastore-deletefail).


datastore-delete:success
------------------------

There are no fields for this activity type.


datastore-delete:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |