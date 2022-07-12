password-copy
=============

Description
-----------
A stored password object was copied, and a new object was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-copysuccess) or a [fail](#password-copyfail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | password      |
| Activity      | copy          |
| Activity Type | password-copy |
| Pretty Name   | Password Copy |
| Legacy Name   |               |

password-copy:success
---------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| src_password |      |           | &#10003;      |

password-copy:fail
------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| src_password |      |           | &#10003;      |