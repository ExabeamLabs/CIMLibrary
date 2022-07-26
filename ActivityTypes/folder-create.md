folder-create
=============

Description
-----------
A folder was created on a an app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | folder        |
| Activity      | create        |
| Activity Type | folder-create |
| Pretty Name   | Folder Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#folder-createsuccess) or a [fail](#folder-createfail).


folder-create:success
---------------------

There are no fields for this activity type.


folder-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |