disk-list
=========

Description
-----------
An enumeration of disk objects took place

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | disk      |
| Activity      | list      |
| Activity Type | disk-list |
| Pretty Name   | Disk List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-listsuccess) or a [fail](#disk-listfail).


disk-list:success
-----------------

There are no fields for this activity type.


disk-list:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |