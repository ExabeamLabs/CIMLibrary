peripheral_device-remove
========================

Description
-----------
A peripheral device device was removed

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | peripheral_device        |
| Activity      | remove                   |
| Activity Type | peripheral_device-remove |
| Pretty Name   | Peripheral_device Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_device-removesuccess) or a [fail](#peripheral_device-removefail).


peripheral_device-remove:success
--------------------------------

There are no fields for this activity type.


peripheral_device-remove:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |