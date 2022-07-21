channel-delete
==============

Description
-----------
A communication channel was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#channel-deletesuccess) or a [fail](#channel-deletefail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | channel        |
| Activity      | delete         |
| Activity Type | channel-delete |
| Pretty Name   | Channel Delete |
| Legacy Name   |                |

channel-delete:success
----------------------

There are no fields for this activity type.


channel-delete:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |