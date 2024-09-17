template-delete
===============

Description
-----------
Template was deleted

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | template        |
| Activity      | delete          |
| Activity Type | template-delete |
| Pretty Name   | Template delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#template-deletesuccess) or a [fail](#template-deletefail).


template-delete:success
-----------------------

There are no fields for this activity type.


template-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |