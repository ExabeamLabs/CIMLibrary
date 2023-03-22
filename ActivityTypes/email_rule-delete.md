email_rule-delete
=================

Description
-----------
An email rule was deleted

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | email_rule        |
| Activity      | delete            |
| Activity Type | email_rule-delete |
| Pretty Name   | Email_rule Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email_rule-deletesuccess) or a [fail](#email_rule-deletefail).


email_rule-delete:success
-------------------------

There are no fields for this activity type.


email_rule-delete:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |