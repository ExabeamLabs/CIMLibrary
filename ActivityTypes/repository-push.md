repository-push
===============

Description
-----------
A git repository was Pushed

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | repository      |
| Activity      | push            |
| Activity Type | repository-push |
| Pretty Name   | Repository Push |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-pushsuccess) or a [fail](#repository-pushfail).


repository-push:success
-----------------------

There are no fields for this activity type.


repository-push:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |