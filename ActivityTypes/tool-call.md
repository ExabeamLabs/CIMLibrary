tool-call
=========

Description
-----------
A request or a declaration for a tool invocation.

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | tool      |
| Activity      | call      |
| Activity Type | tool-call |
| Pretty Name   | Tool Call |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#tool-callsuccess) or a [fail](#tool-callfail).


tool-call:success
-----------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.