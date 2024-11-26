dashboard-delete
================

Description
-----------
A dashboard was deleted 

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | report           |
| Activity      | delete           |
| Activity Type | dashboard-delete |
| Pretty Name   | Dashboard Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-deletesuccess) or a [fail](#dashboard-deletefail).


dashboard-delete:success
------------------------

There are no fields for this activity type.


dashboard-delete:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |