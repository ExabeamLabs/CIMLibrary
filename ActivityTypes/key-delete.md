key-delete
==========

Description
-----------
A global key object was deleted

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | key        |
| Activity      | delete     |
| Activity Type | key-delete |
| Pretty Name   | Key Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#key-deletesuccess) or a [fail](#key-deletefail).


key-delete:success
------------------

There are no fields for this activity type.


key-delete:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |