disk-remove
===========

Description
-----------
A disk attachment was reversed and a disk was removed from a machine

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | disk        |
| Activity      | remove      |
| Activity Type | disk-remove |
| Pretty Name   | Disk Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-removesuccess) or a [fail](#disk-removefail).


disk-remove:success
-------------------

There are no fields for this activity type.


disk-remove:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |