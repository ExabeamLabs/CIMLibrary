image-write
===========

Description
-----------
A VM image object was created or modified, only used as a catch all if create or modify cannot be determined

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-writesuccess) or a [fail](#image-writefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | image       |
| Activity      | write       |
| Activity Type | image-write |
| Pretty Name   | Image Write |
| Legacy Name   |             |

image-write:success
-------------------

There are no fields for this activity type.


image-write:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |