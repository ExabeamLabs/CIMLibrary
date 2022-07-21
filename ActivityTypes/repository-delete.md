repository-delete
=================

Description
-----------
A git repository was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-deletesuccess) or a [fail](#repository-deletefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | repository        |
| Activity      | delete            |
| Activity Type | repository-delete |
| Pretty Name   | Repository Delete |
| Legacy Name   |                   |

repository-delete:success
-------------------------

There are no fields for this activity type.


repository-delete:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |