visualization-schedule
======================

Description
-----------
A request to schedule a visualization was made

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | visualization          |
| Activity      | schedule               |
| Activity Type | visualization-schedule |
| Pretty Name   | Visualization Schedule |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-schedulesuccess) or a [fail](#visualization-schedulefail).


visualization-schedule:success
------------------------------

There are no fields for this activity type.


visualization-schedule:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |