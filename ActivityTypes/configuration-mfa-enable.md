configuration-mfa-enable
========================

Description
-----------
The global mfa configuration of an application was changed to enabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-mfa-enablesuccess) or a [fail](#configuration-mfa-enablefail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | configuration            |
| Activity      | mfa-enable               |
| Activity Type | configuration-mfa-enable |
| Pretty Name   | Configuration Mfa Enable |
| Legacy Name   |                          |

configuration-mfa-enable:success
--------------------------------

There are no fields for this activity type.


configuration-mfa-enable:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |