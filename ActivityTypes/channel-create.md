channel-create
==============

Description
-----------
A communication channel was created

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | channel        |
| Activity      | create         |
| Activity Type | channel-create |
| Pretty Name   | Channel Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#channel-createsuccess) or a [fail](#channel-createfail).


channel-create:success
----------------------

There are no fields for this activity type.


channel-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |