email_rule-modify
=================

Description
-----------
The content or configuration of an email rule was modified

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | email_rule        |
| Activity      | modify            |
| Activity Type | email_rule-modify |
| Pretty Name   | Email_rule Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email_rule-modifysuccess) or a [fail](#email_rule-modifyfail).


email_rule-modify:success
-------------------------

There are no fields for this activity type.


email_rule-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |