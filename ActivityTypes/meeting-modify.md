meeting-modify
==============

Description
-----------
A web meeting's information was updated

The possible fields for this activity type will vary depending on whether the activity was a [success](#meeting-modifysuccess) or a [fail](#meeting-modifyfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | meeting        |
| Activity      | modify         |
| Activity Type | meeting-modify |
| Pretty Name   | Meeting Modify |
| Legacy Name   |                |

meeting-modify:success
----------------------

There are no fields for this activity type.


meeting-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |