password-use
============

Description
-----------
A stored password was used by a user

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-usesuccess) or a [fail](#password-usefail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | password     |
| Activity      | use          |
| Activity Type | password-use |
| Pretty Name   | Password Use |
| Legacy Name   |              |

password-use:success
--------------------

There are no fields for this activity type.


password-use:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |