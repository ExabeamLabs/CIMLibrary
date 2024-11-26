dashboard-schedule
==================

Description
-----------
A request to schedule a dashboard was made

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | dashboard          |
| Activity      | schedule           |
| Activity Type | dashboard-schedule |
| Pretty Name   | Dashboard Schedule |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-schedulesuccess) or a [fail](#dashboard-schedulefail).


dashboard-schedule:success
--------------------------

There are no fields for this activity type.


dashboard-schedule:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |