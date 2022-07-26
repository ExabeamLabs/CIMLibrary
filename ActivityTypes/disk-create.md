disk-create
===========

Description
-----------
A disk volume object was created

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | disk        |
| Activity      | create      |
| Activity Type | disk-create |
| Pretty Name   | Disk Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-createsuccess) or a [fail](#disk-createfail).


disk-create:success
-------------------

There are no fields for this activity type.


disk-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |