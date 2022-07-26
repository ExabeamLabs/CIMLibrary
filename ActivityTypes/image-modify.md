image-modify
============

Description
-----------
The properties of a VM image were changed

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | image        |
| Activity      | modify       |
| Activity Type | image-modify |
| Pretty Name   | Image Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-modifysuccess) or a [fail](#image-modifyfail).


image-modify:success
--------------------

There are no fields for this activity type.


image-modify:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |