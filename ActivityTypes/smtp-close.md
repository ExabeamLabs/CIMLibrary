smtp-close
==========

Description
-----------
A SMTP session was terminated

The possible fields for this activity type will vary depending on whether the activity was a [success](#smtp-closesuccess) or a [fail](#smtp-closefail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | smtp       |
| Activity      | close      |
| Activity Type | smtp-close |
| Pretty Name   | Smtp Close |
| Legacy Name   |            |

smtp-close:success
------------------

There are no fields for this activity type.


smtp-close:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |