image-list
==========

Description
-----------
An enumeration of VM image objects took place

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | image      |
| Activity      | list       |
| Activity Type | image-list |
| Pretty Name   | Image List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#image-listsuccess) or a [fail](#image-listfail).


image-list:success
------------------

There are no fields for this activity type.


image-list:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |