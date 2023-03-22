branch-modify
=============

Description
-----------
A git branch properties were modified

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | branch        |
| Activity      | modify        |
| Activity Type | branch-modify |
| Pretty Name   | Branch Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#branch-modifysuccess) or a [fail](#branch-modifyfail).


branch-modify:success
---------------------

There are no fields for this activity type.


branch-modify:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |