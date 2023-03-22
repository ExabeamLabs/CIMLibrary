report-read
===========

Description
-----------
A request to read a report was made

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | report      |
| Activity      | read        |
| Activity Type | report-read |
| Pretty Name   | Report Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#report-readsuccess) or a [fail](#report-readfail).


report-read:success
-------------------

There are no fields for this activity type.


report-read:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |