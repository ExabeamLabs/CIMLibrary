collector-create
================

Description
-----------
Collector Created

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | collector        |
| Activity      | create           |
| Activity Type | collector-create |
| Pretty Name   | Collector Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#collector-createsuccess) or a [fail](#collector-createfail).


collector-create:success
------------------------

There are no fields for this activity type.


collector-create:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |