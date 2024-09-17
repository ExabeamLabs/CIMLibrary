collector-modify
================

Description
-----------
Collector was modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | collector        |
| Activity      | modify           |
| Activity Type | collector-modify |
| Pretty Name   | Collector modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#collector-modifysuccess) or a [fail](#collector-modifyfail).


collector-modify:success
------------------------

There are no fields for this activity type.


collector-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |