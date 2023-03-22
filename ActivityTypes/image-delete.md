image-delete
============

Description
-----------
A VM image was deleted

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | image        |
| Activity      | delete       |
| Activity Type | image-delete |
| Pretty Name   | Image Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-deletesuccess) or a [fail](#image-deletefail).


image-delete:success
--------------------

There are no fields for this activity type.


image-delete:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |