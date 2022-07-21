peripheral_storage-insert
=========================

Description
-----------
A peripheral storage device was inserted

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_storage-insertsuccess) or a [fail](#peripheral_storage-insertfail).

| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | peripheral_storage        |
| Activity      | insert                    |
| Activity Type | peripheral_storage-insert |
| Pretty Name   | Peripheral_storage Insert |
| Legacy Name   |                           |

peripheral_storage-insert:success
---------------------------------

There are no fields for this activity type.


peripheral_storage-insert:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |