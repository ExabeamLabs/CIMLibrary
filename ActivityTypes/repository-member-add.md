repository-member-add
=====================

Description
-----------
A repository member was added to a git repositry

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-member-addsuccess) or a [fail](#repository-member-addfail).

| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | repository            |
| Activity      | member-add            |
| Activity Type | repository-member-add |
| Pretty Name   | Repository Member Add |
| Legacy Name   |                       |

repository-member-add:success
-----------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |

repository-member-add:fail
--------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |