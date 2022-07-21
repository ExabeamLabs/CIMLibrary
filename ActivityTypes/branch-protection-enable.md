branch-protection-enable
========================

Description
-----------
The protection status of a git branch was changed to enabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#branch-protection-enablesuccess) or a [fail](#branch-protection-enablefail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | branch                   |
| Activity      | protection-enable        |
| Activity Type | branch-protection-enable |
| Pretty Name   | Branch Protection Enable |
| Legacy Name   |                          |

branch-protection-enable:success
--------------------------------

There are no fields for this activity type.


branch-protection-enable:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |