repository-member-add
=====================

Description
-----------
A repository member was added to a git repositry

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | repository            |
| Activity      | member-add            |
| Activity Type | repository-member-add |
| Pretty Name   | Repository Member Add |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-member-addsuccess) or a [fail](#repository-member-addfail).


repository-member-add:success
-----------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |

repository-member-add:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| member         |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |