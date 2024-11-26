dashboard-publish
=================

Description
-----------
A request to publish a dashboard was made

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | dashboard         |
| Activity      | publish           |
| Activity Type | dashboard-publish |
| Pretty Name   | Dashboard Publish |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-publishsuccess) or a [fail](#dashboard-publishfail).


dashboard-publish:success
-------------------------

There are no fields for this activity type.


dashboard-publish:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |