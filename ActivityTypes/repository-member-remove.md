repository-member-remove
========================

Description
-----------
A repository member was removed from a git repositry

The possible fields for this activity type will vary depending on whether the activity was a [success](#repository-member-removesuccess) or a [fail](#repository-member-removefail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | repository               |
| Activity      | member-remove            |
| Activity Type | repository-member-remove |
| Pretty Name   | Repository Member Remove |
| Legacy Name   |                          |

repository-member-remove:success
--------------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |

repository-member-remove:fail
-----------------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| member |      |           | &#10003;      |