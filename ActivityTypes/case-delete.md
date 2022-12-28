case-delete
===========

Description
-----------
A security incident was deleted on a security product

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | case        |
| Activity      | delete      |
| Activity Type | case-delete |
| Pretty Name   | Case Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#case-deletesuccess) or a [fail](#case-deletefail).


case-delete:success
-------------------

There are no fields for this activity type.


case-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |