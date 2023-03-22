folder-delete
=============

Description
-----------
A folder was deleted on an app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | folder        |
| Activity      | delete        |
| Activity Type | folder-delete |
| Pretty Name   | Folder Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#folder-deletesuccess) or a [fail](#folder-deletefail).


folder-delete:success
---------------------

There are no fields for this activity type.


folder-delete:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |