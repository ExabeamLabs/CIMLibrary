channel-modify
==============

Description
-----------
The properties of a communication channel were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#channel-modifysuccess) or a [fail](#channel-modifyfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | channel        |
| Activity      | modify         |
| Activity Type | channel-modify |
| Pretty Name   | Channel Modify |
| Legacy Name   |                |

channel-modify:success
----------------------

There are no fields for this activity type.


channel-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |