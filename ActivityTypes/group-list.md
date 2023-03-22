group-list
==========

Description
-----------
An enumeration of multiple groups took place

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | group      |
| Activity      | list       |
| Activity Type | group-list |
| Pretty Name   | Group List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-listsuccess) or a [fail](#group-listfail).


group-list:success
------------------

There are no fields for this activity type.


group-list:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |