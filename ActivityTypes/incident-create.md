incident-create
===============

Description
-----------
A security incident was created on a security product

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | incident        |
| Activity      | create          |
| Activity Type | incident-create |
| Pretty Name   | Incident Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#incident-createsuccess) or a [fail](#incident-createfail).


incident-create:success
-----------------------

There are no fields for this activity type.


incident-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |