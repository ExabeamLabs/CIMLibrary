ssl-start
=========

Description
-----------
A SSL session was initiated

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ssl       |
| Activity      | start     |
| Activity Type | ssl-start |
| Pretty Name   | Ssl Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssl-startsuccess) or a [fail](#ssl-startfail).


ssl-start:success
-----------------

There are no fields for this activity type.


ssl-start:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |