peripheral_storage-remove
=========================

Description
-----------
A peripheral storage device was removed

Parameters
----------
| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | peripheral_storage        |
| Activity      | remove                    |
| Activity Type | peripheral_storage-remove |
| Pretty Name   | Peripheral_storage Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_storage-removesuccess) or a [fail](#peripheral_storage-removefail).


peripheral_storage-remove:success
---------------------------------

There are no fields for this activity type.


peripheral_storage-remove:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |