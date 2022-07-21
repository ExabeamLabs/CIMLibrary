port-enable
===========

Description
-----------
A port was enabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#port-enablesuccess) or a [fail](#port-enablefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | port        |
| Activity      | enable      |
| Activity Type | port-enable |
| Pretty Name   | Port Enable |
| Legacy Name   |             |

port-enable:success
-------------------

There are no fields for this activity type.


port-enable:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |