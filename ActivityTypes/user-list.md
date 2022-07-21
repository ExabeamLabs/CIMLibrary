user-list
=========

Description
-----------
An enumeration of multiple users took place

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-listsuccess) or a [fail](#user-listfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | user      |
| Activity      | list      |
| Activity Type | user-list |
| Pretty Name   | User List |
| Legacy Name   |           |

user-list:success
-----------------

There are no fields for this activity type.


user-list:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |