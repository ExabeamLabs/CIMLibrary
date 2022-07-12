group-member-move
=================

Description
-----------
A group member was moved from one group to another

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-movesuccess) or a [fail](#group-member-movefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | group             |
| Activity      | member-move       |
| Activity Type | group-member-move |
| Pretty Name   | Group Member Move |
| Legacy Name   |                   |

group-member-move:success
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_group_name |      |           | &#10003;      |

group-member-move:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_group_name |      |           | &#10003;      |