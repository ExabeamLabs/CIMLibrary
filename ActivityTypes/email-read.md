email-read
==========

Description
-----------
An email in an inbox was deleted and read

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | email      |
| Activity      | read       |
| Activity Type | email-read |
| Pretty Name   | Email Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-readsuccess) or a [fail](#email-readfail).


email-read:success
------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| email_subject |      |           | &#10003;      |

email-read:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| email_subject  |      |           | &#10003;      |