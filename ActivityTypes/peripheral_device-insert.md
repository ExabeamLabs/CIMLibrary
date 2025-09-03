peripheral_device-insert
========================

Description
-----------
A peripheral device was inserted

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | peripheral_device        |
| Activity      | insert                   |
| Activity Type | peripheral_device-insert |
| Pretty Name   | Peripheral_device Insert |

Legacy Names
------------
| Success        | Fail           |
| -------------- | -------------- |
| usb-insert<br> | usb-insert<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_device-insertsuccess) or a [fail](#peripheral_device-insertfail).


peripheral_device-insert:success
--------------------------------

There are no fields for this activity type.


peripheral_device-insert:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |