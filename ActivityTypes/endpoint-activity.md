endpoint-activity
=================

Description
-----------
A generic activity took place in an endpoint (catch all)

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | endpoint          |
| Activity      | activity          |
| Activity Type | endpoint-activity |
| Pretty Name   | Endpoint Activity |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-activitysuccess) or a [fail](#endpoint-activityfail).


endpoint-activity:success
-------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| operation |      |           | &#10003;      |

endpoint-activity:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| operation      |      |           | &#10003;      |