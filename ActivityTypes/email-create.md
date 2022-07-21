email-create
============

Description
-----------
A user has created and started to write an email or a draft of an email

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-createsuccess) or a [fail](#email-createfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | email        |
| Activity      | create       |
| Activity Type | email-create |
| Pretty Name   | Email Create |
| Legacy Name   |              |

email-create:success
--------------------

There are no fields for this activity type.


email-create:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |