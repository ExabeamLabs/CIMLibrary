collector-delete
================

Description
-----------
Collector was deleted

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | collector        |
| Activity      | delete           |
| Activity Type | collector-delete |
| Pretty Name   | Collector delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#collector-deletesuccess) or a [fail](#collector-deletefail).


collector-delete:success
------------------------

There are no fields for this activity type.


collector-delete:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |