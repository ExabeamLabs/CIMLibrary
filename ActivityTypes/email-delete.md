email-delete
============

Description
-----------
An email in an inbox was deleted

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | email        |
| Activity      | delete       |
| Activity Type | email-delete |
| Pretty Name   | Email Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-deletesuccess) or a [fail](#email-deletefail).


email-delete:success
--------------------

There are no fields for this activity type.


email-delete:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |