file-property-delete
====================

Description
-----------
A property of a file was deleted

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | file                 |
| Activity      | property-delete      |
| Activity Type | file-property-delete |
| Pretty Name   | File Property Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-property-deletesuccess) or a [fail](#file-property-deletefail).


file-property-delete:success
----------------------------

There are no fields for this activity type.


file-property-delete:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |