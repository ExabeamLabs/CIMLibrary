playbook-disable
================

Description
-----------
Playbook was disabled

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | playbook         |
| Activity      | disable          |
| Activity Type | playbook-disable |
| Pretty Name   | Playbook Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-disablesuccess) or a [fail](#playbook-disablefail).


playbook-disable:success
------------------------

There are no fields for this activity type.


playbook-disable:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |