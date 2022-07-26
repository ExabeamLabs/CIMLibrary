email-move
==========

Description
-----------
An email in an inbox folder was moved to another inbox folder

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | email      |
| Activity      | move       |
| Activity Type | email-move |
| Pretty Name   | Email Move |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-movesuccess) or a [fail](#email-movefail).


email-move:success
------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_folder |      |           | &#10003;      |
| src_email_folder  |      |           | &#10003;      |

email-move:fail
---------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_folder |      |           | &#10003;      |
| failure_code      |      | &#10003;  |               |
| src_email_folder  |      |           | &#10003;      |
| failure_reason    |      | &#10003;  |               |