folder-modify
=============

Description
-----------
A folder properties or configuration were modified on an app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | folder        |
| Activity      | modify        |
| Activity Type | folder-modify |
| Pretty Name   | Folder Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#folder-modifysuccess) or a [fail](#folder-modifyfail).


folder-modify:success
---------------------

There are no fields for this activity type.


folder-modify:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |