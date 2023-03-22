disk-delete
===========

Description
-----------
A disk volume object was deleted

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | disk        |
| Activity      | delete      |
| Activity Type | disk-delete |
| Pretty Name   | Disk Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-deletesuccess) or a [fail](#disk-deletefail).


disk-delete:success
-------------------

There are no fields for this activity type.


disk-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |