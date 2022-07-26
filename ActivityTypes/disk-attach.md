disk-attach
===========

Description
-----------
A disk volume was attached to a machine

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | disk        |
| Activity      | attach      |
| Activity Type | disk-attach |
| Pretty Name   | Disk Attach |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-attachsuccess) or a [fail](#disk-attachfail).


disk-attach:success
-------------------

There are no fields for this activity type.


disk-attach:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |