playbook-modify
===============

Description
-----------
Playbook was Modified

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | playbook        |
| Activity      | modify          |
| Activity Type | playbook-modify |
| Pretty Name   | Playbook Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-modifysuccess) or a [fail](#playbook-modifyfail).


playbook-modify:success
-----------------------

There are no fields for this activity type.


playbook-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |