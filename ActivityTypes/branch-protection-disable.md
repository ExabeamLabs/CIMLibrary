branch-protection-disable
=========================

Description
-----------
The protection status of a git branch was changed to disabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#branch-protection-disablesuccess) or a [fail](#branch-protection-disablefail).

| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | branch                    |
| Activity      | protection-disable        |
| Activity Type | branch-protection-disable |
| Pretty Name   | Branch Protection Disable |
| Legacy Name   |                           |

branch-protection-disable:success
---------------------------------

There are no fields for this activity type.


branch-protection-disable:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |