dashboard-modify
================

Description
-----------
A request to modify a dashboard was made

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | dashboard        |
| Activity      | modify           |
| Activity Type | dashboard-modify |
| Pretty Name   | Dashboard Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-modifysuccess) or a [fail](#dashboard-modifyfail).


dashboard-modify:success
------------------------

There are no fields for this activity type.


dashboard-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |