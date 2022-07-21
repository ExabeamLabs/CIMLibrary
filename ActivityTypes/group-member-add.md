group-member-add
================

Description
-----------
A group member was added to a group

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-addsuccess) or a [fail](#group-member-addfail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | group            |
| Activity      | member-add       |
| Activity Type | group-member-add |
| Pretty Name   | Group Member Add |
| Legacy Name   |                  |

group-member-add:success
------------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| member | &#10003; | &#10003;  |               |

group-member-add:fail
---------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| member         | &#10003; | &#10003;  |               |
| failure_reason |          | &#10003;  |               |