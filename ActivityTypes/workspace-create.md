workspace-create
================

Description
-----------
A workspace was created

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | workspace        |
| Activity      | create           |
| Activity Type | workspace-create |
| Pretty Name   | Workspace Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#workspace-createsuccess) or a [fail](#workspace-createfail).


workspace-create:success
------------------------

There are no fields for this activity type.


workspace-create:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |