registry-delete
===============

Description
-----------
A registry object wa deleted

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | delete          |
| Activity Type | registry-delete |
| Pretty Name   | Registry Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-deletesuccess) or a [fail](#registry-deletefail).


registry-delete:success
-----------------------

There are no fields for this activity type.


registry-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |