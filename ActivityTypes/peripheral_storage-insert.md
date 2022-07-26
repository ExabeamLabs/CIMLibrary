peripheral_storage-insert
=========================

Description
-----------
A peripheral storage device was inserted

Parameters
----------
| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | peripheral_storage        |
| Activity      | insert                    |
| Activity Type | peripheral_storage-insert |
| Pretty Name   | Peripheral_storage Insert |

Legacy Names
------------
| Success        | Fail           |
| -------------- | -------------- |
| usb-insert<br> | usb-insert<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_storage-insertsuccess) or a [fail](#peripheral_storage-insertfail).


peripheral_storage-insert:success
---------------------------------

There are no fields for this activity type.


peripheral_storage-insert:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |