repository-modify
=================

Description
-----------
The properties or configuration of a git repository were modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-modifysuccess) or a [fail](#repository-modifyfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | repository        |
| Activity      | modify            |
| Activity Type | repository-modify |
| Pretty Name   | Repository Modify |
| Legacy Name   |                   |

repository-modify:success
-------------------------

There are no fields for this activity type.


repository-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |