port-block
==========

Description
-----------
A port was blocked, dropping traffic that comes throug

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | port       |
| Activity      | block      |
| Activity Type | port-block |
| Pretty Name   | Port Block |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#port-blocksuccess) or a [fail](#port-blockfail).


port-block:success
------------------

There are no fields for this activity type.


port-block:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |