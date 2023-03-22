file-property-read
==================

Description
-----------
The properties of a file were read

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | file               |
| Activity      | property-read      |
| Activity Type | file-property-read |
| Pretty Name   | File Property Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-property-readsuccess) or a [fail](#file-property-readfail).


file-property-read:success
--------------------------

There are no fields for this activity type.


file-property-read:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |