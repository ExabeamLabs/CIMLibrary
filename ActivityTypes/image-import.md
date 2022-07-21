image-import
============

Description
-----------
An import process for a VM image was initiated in the system

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-importsuccess) or a [fail](#image-importfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | image        |
| Activity      | import       |
| Activity Type | image-import |
| Pretty Name   | Image Import |
| Legacy Name   |              |

image-import:success
--------------------

There are no fields for this activity type.


image-import:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |