repository-member-remove
========================

Description
-----------
A repository member was removed from a git repositry

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | repository               |
| Activity      | member-remove            |
| Activity Type | repository-member-remove |
| Pretty Name   | Repository Member Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-member-removesuccess) or a [fail](#repository-member-removefail).


repository-member-remove:success
--------------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |

repository-member-remove:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| member         |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |