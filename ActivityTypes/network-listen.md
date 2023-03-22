network-listen
==============

Description
-----------
A network process or service has started listening for connections

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | network        |
| Activity      | listen         |
| Activity Type | network-listen |
| Pretty Name   | Network Listen |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-listensuccess) or a [fail](#network-listenfail).


network-listen:success
----------------------

There are no fields for this activity type.


network-listen:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |