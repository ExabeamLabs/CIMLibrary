disk-read
=========

Description
-----------
The content of a disk\volume object was read

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-readsuccess) or a [fail](#disk-readfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | disk      |
| Activity      | read      |
| Activity Type | disk-read |
| Pretty Name   | Disk Read |
| Legacy Name   |           |

disk-read:success
-----------------

There are no fields for this activity type.


disk-read:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |