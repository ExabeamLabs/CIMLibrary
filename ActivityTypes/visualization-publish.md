visualization-publish
=====================

Description
-----------
A request to publish a visualization was made

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | visualization         |
| Activity      | publish               |
| Activity Type | visualization-publish |
| Pretty Name   | Visualization Publish |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-publishsuccess) or a [fail](#visualization-publishfail).


visualization-publish:success
-----------------------------

There are no fields for this activity type.


visualization-publish:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |