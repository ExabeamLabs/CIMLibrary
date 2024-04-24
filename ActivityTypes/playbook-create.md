playbook-create
===============

Description
-----------
Playbook Created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | playbook        |
| Activity      | create          |
| Activity Type | playbook-create |
| Pretty Name   | Playbook Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#playbook-createsuccess) or a [fail](#playbook-createfail).


playbook-create:success
-----------------------

There are no fields for this activity type.


playbook-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |