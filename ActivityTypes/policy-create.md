policy-create
=============

Description
-----------
A security policy document was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-createsuccess) or a [fail](#policy-createfail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | policy        |
| Activity      | create        |
| Activity Type | policy-create |
| Pretty Name   | Policy Create |
| Legacy Name   |               |

policy-create:success
---------------------

There are no fields for this activity type.


policy-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |