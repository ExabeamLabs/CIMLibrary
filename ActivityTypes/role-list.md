role-list
=========

Description
-----------
An enumeration of security roles took place

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-listsuccess) or a [fail](#role-listfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | role      |
| Activity      | list      |
| Activity Type | role-list |
| Pretty Name   | Role List |
| Legacy Name   |           |

role-list:success
-----------------

There are no fields for this activity type.


role-list:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |