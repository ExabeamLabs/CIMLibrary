repository-move
===============

Description
-----------
The location of a git repository was changed

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | repository      |
| Activity      | move            |
| Activity Type | repository-move |
| Pretty Name   | Repository Move |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-movesuccess) or a [fail](#repository-movefail).


repository-move:success
-----------------------

There are no fields for this activity type.


repository-move:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |