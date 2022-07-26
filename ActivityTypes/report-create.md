report-create
=============

Description
-----------
A report was created on an app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | report        |
| Activity      | create        |
| Activity Type | report-create |
| Pretty Name   | Report Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#report-createsuccess) or a [fail](#report-createfail).


report-create:success
---------------------

There are no fields for this activity type.


report-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |