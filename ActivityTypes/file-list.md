file-list
=========

Description
-----------
A file enumeration took place

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | file      |
| Activity      | list      |
| Activity Type | file-list |
| Pretty Name   | File List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-listsuccess) or a [fail](#file-listfail).


file-list:success
-----------------

There are no fields for this activity type.


file-list:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |