repository-pull
===============

Description
-----------
A git repository was Pulled

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | repository      |
| Activity      | pull            |
| Activity Type | repository-pull |
| Pretty Name   | Repository Pull |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-pullsuccess) or a [fail](#repository-pullfail).


repository-pull:success
-----------------------

There are no fields for this activity type.


repository-pull:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |