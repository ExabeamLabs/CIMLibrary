network-close
=============

Description
-----------
A network session was terminated

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | network       |
| Activity      | close         |
| Activity Type | network-close |
| Pretty Name   | Network Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-closesuccess) or a [fail](#network-closefail).


network-close:success
---------------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| dest_external_country |      | &#10003;  |               |

network-close:fail
------------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| failure_code          |      | &#10003;  |               |
| dest_external_country |      | &#10003;  |               |
| failure_reason        |      | &#10003;  |               |