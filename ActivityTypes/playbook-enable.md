playbook-enable
===============

Description
-----------
Playbook was enabled

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | playbook        |
| Activity      | enable          |
| Activity Type | playbook-enable |
| Pretty Name   | Playbook Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-enablesuccess) or a [fail](#playbook-enablefail).


playbook-enable:success
-----------------------

There are no fields for this activity type.


playbook-enable:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |