ssh-close
=========

Description
-----------
A SSH session was terminated

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ssh       |
| Activity      | close     |
| Activity Type | ssh-close |
| Pretty Name   | Ssh Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssh-closesuccess) or a [fail](#ssh-closefail).


ssh-close:success
-----------------

There are no fields for this activity type.


ssh-close:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |