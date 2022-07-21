configuration-read
==================

Description
-----------
The global configuration of an application or a program was read

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-readsuccess) or a [fail](#configuration-readfail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | configuration      |
| Activity      | read               |
| Activity Type | configuration-read |
| Pretty Name   | Configuration Read |
| Legacy Name   |                    |

configuration-read:success
--------------------------

There are no fields for this activity type.


configuration-read:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |