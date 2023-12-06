report-delete
=============

Description
-----------
A report was deleted on an app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | report        |
| Activity      | delete        |
| Activity Type | report-delete |
| Pretty Name   | Report Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#report-deletesuccess) or a [fail](#report-deletefail).


report-delete:success
---------------------

There are no fields for this activity type.


report-delete:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |