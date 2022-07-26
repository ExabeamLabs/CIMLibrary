incident-delete
===============

Description
-----------
A security incident was deleted on a security product

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | incident        |
| Activity      | delete          |
| Activity Type | incident-delete |
| Pretty Name   | Incident Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#incident-deletesuccess) or a [fail](#incident-deletefail).


incident-delete:success
-----------------------

There are no fields for this activity type.


incident-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |