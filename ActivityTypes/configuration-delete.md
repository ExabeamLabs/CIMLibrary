configuration-delete
====================

Description
-----------
The global configuration of an application or a program was deleted

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | configuration        |
| Activity      | delete               |
| Activity Type | configuration-delete |
| Pretty Name   | Configuration Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-deletesuccess) or a [fail](#configuration-deletefail).


configuration-delete:success
----------------------------

There are no fields for this activity type.


configuration-delete:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |