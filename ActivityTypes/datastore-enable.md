datastore-enable
================

Description
-----------
The status of a virtualization datastore was set to enable

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-enablesuccess) or a [fail](#datastore-enablefail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | datastore        |
| Activity      | enable           |
| Activity Type | datastore-enable |
| Pretty Name   | Datastore Enable |
| Legacy Name   |                  |

datastore-enable:success
------------------------

There are no fields for this activity type.


datastore-enable:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |