process-open
============

Description
-----------
A process object was opened to access

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-opensuccess) or a [fail](#process-openfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | process      |
| Activity      | open         |
| Activity Type | process-open |
| Pretty Name   | Process Open |
| Legacy Name   |              |

process-open:success
--------------------

There are no fields for this activity type.


process-open:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |