image-create
============

Description
-----------
A VM image was created

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | image        |
| Activity      | create       |
| Activity Type | image-create |
| Pretty Name   | Image Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-createsuccess) or a [fail](#image-createfail).


image-create:success
--------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| image_publisher |      |           | &#10003;      |

image-create:fail
-----------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| image_publisher |      |           | &#10003;      |
| failure_reason  |      | &#10003;  |               |