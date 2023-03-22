branch-protection-modify
========================

Description
-----------
The protection configuration of a git branch was changed

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | branch                   |
| Activity      | protection-modify        |
| Activity Type | branch-protection-modify |
| Pretty Name   | Branch Protection Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#branch-protection-modifysuccess) or a [fail](#branch-protection-modifyfail).


branch-protection-modify:success
--------------------------------

There are no fields for this activity type.


branch-protection-modify:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |