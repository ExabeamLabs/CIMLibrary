radius-session
==============

Description
-----------
A summary of a complete RADIUS network session

The possible fields for this activity type will vary depending on whether the activity was a [success](#radius-session	success) or a [fail](#radius-session	fail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | radius          |
| Activity      | session	        |
| Activity Type | radius-session	 |
| Pretty Name   | Radius Session	 |
| Legacy Name   |                 |

radius-session	:success
-----------------------

There are no fields for this activity type.


radius-session	:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |