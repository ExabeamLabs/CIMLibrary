file-share
==========

Description
-----------
The share of a file was created, allowing it to be shared with other users or endpoints

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-sharesuccess) or a [fail](#file-sharefail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | file       |
| Activity      | share      |
| Activity Type | file-share |
| Pretty Name   | File Share |
| Legacy Name   |            |

file-share:success
------------------

There are no fields for this activity type.


file-share:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |