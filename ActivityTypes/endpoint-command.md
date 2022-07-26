endpoint-command
================

Description
-----------
A virtual command was set to execute on an endpoint object. Only used in VMs. 

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | endpoint         |
| Activity      | command          |
| Activity Type | endpoint-command |
| Pretty Name   | Endpoint Command |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-commandsuccess) or a [fail](#endpoint-commandfail).


endpoint-command:success
------------------------

There are no fields for this activity type.


endpoint-command:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |