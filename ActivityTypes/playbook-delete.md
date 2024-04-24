playbook-delete
===============

Description
-----------
Playbook was Deleted

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | playbook        |
| Activity      | delete          |
| Activity Type | playbook-delete |
| Pretty Name   | Playbook delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-deletesuccess) or a [fail](#playbook-deletefail).


playbook-delete:success
-----------------------

There are no fields for this activity type.


playbook-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |