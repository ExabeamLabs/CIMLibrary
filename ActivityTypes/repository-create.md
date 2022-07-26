repository-create
=================

Description
-----------
A git repository was created

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | repository        |
| Activity      | create            |
| Activity Type | repository-create |
| Pretty Name   | Repository Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-createsuccess) or a [fail](#repository-createfail).


repository-create:success
-------------------------

There are no fields for this activity type.


repository-create:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |