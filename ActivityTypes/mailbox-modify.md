mailbox-modify
==============

Description
-----------
The properties or configuration of an email mailbox were changed

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | mailbox        |
| Activity      | modify         |
| Activity Type | mailbox-modify |
| Pretty Name   | Mailbox Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-modifysuccess) or a [fail](#mailbox-modifyfail).


mailbox-modify:success
----------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| email_recipients |      | &#10003;  |               |
| email_domain     |      | &#10003;  |               |

mailbox-modify:fail
-------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| email_recipients |      | &#10003;  |               |
| failure_code     |      | &#10003;  |               |
| email_domain     |      | &#10003;  |               |
| failure_reason   |      | &#10003;  |               |