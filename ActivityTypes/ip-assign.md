ip-assign
=========

Description
-----------
An IP was dispensed and is in use

The possible fields for this activity type will vary depending on whether the activity was a [success](#ip-assignsuccess) or a [fail](#ip-assignfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ip        |
| Activity      | assign    |
| Activity Type | ip-assign |
| Pretty Name   | Ip Assign |
| Legacy Name   |           |

ip-assign:success
-----------------

There are no fields for this activity type.


ip-assign:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |