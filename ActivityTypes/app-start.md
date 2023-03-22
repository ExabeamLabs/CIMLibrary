app-start
=========

Description
-----------
The application was initiazlied

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | app       |
| Activity      | start     |
| Activity Type | app-start |
| Pretty Name   | App Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-startsuccess) or a [fail](#app-startfail).


app-start:success
-----------------

There are no fields for this activity type.


app-start:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |