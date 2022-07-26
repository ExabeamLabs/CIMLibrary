ssh-start
=========

Description
-----------
A SSH sesssion was initiated

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ssh       |
| Activity      | start     |
| Activity Type | ssh-start |
| Pretty Name   | Ssh Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssh-startsuccess) or a [fail](#ssh-startfail).


ssh-start:success
-----------------

There are no fields for this activity type.


ssh-start:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |