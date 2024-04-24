branch-create
=============

Description
-----------
A git branch was created

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | branch        |
| Activity      | create        |
| Activity Type | branch-create |
| Pretty Name   | Branch Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#branch-createsuccess) or a [fail](#branch-createfail).


branch-create:success
---------------------

There are no fields for this activity type.


branch-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |