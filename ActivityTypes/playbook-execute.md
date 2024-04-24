playbook-execute
================

Description
-----------
Playbook was execute

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | playbook         |
| Activity      | execute          |
| Activity Type | playbook-execute |
| Pretty Name   | Playbook Execute |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-executesuccess) or a [fail](#playbook-executefail).


playbook-execute:success
------------------------

There are no fields for this activity type.


playbook-execute:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |