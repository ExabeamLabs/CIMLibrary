handle-close
============

Description
-----------
A windows handle was closed

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | handle       |
| Activity      | close        |
| Activity Type | handle-close |
| Pretty Name   | Handle Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#handle-closesuccess) or a [fail](#handle-closefail).


handle-close:success
--------------------

There are no fields for this activity type.


handle-close:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |