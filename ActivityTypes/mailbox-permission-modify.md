mailbox-permission-modify
=========================

Description
-----------
The permissions that apply to an email mailbox were changed

Parameters
----------
| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | mailbox                   |
| Activity      | permission-modify         |
| Activity Type | mailbox-permission-modify |
| Pretty Name   | Mailbox Permission Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-permission-modifysuccess) or a [fail](#mailbox-permission-modifyfail).


mailbox-permission-modify:success
---------------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_user |      | &#10003;  |               |
| user      |      | &#10003;  |               |

mailbox-permission-modify:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| dest_user      |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| user           |      | &#10003;  |               |