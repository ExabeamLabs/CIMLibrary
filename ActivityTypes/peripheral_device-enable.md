peripheral_device-enable
========================

Description
-----------
A peripheral device was enabled

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | peripheral_device        |
| Activity      | enable                   |
| Activity Type | peripheral_device-enable |
| Pretty Name   | Peripheral_device Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_device-enablesuccess) or a [fail](#peripheral_device-enablefail).


peripheral_device-enable:success
--------------------------------

There are no fields for this activity type.


peripheral_device-enable:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |