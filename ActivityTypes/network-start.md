network-start
=============

Description
-----------
A network session was initiated

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | network       |
| Activity      | start         |
| Activity Type | network-start |
| Pretty Name   | Network Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-startsuccess) or a [fail](#network-startfail).


network-start:success
---------------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| dest_external_country |      | &#10003;  |               |

network-start:fail
------------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| failure_code          |      | &#10003;  |               |
| dest_external_country |      | &#10003;  |               |
| failure_reason        |      | &#10003;  |               |