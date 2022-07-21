email_rule-create
=================

Description
-----------
An email rule was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#email_rule-createsuccess) or a [fail](#email_rule-createfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | email_rule        |
| Activity      | create            |
| Activity Type | email_rule-create |
| Pretty Name   | Email_rule Create |
| Legacy Name   |                   |

email_rule-create:success
-------------------------

There are no fields for this activity type.


email_rule-create:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |