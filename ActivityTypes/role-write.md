role-write
==========

Description
-----------
A role identity was created or modified, only used as a catch all if create or modify cannot be determined

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-writesuccess) or a [fail](#role-writefail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | role       |
| Activity      | write      |
| Activity Type | role-write |
| Pretty Name   | Role Write |
| Legacy Name   |            |

role-write:success
------------------

There are no fields for this activity type.


role-write:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |