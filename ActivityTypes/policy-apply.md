policy-apply
============

Description
-----------
A security policy was enforced on the system or the object

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-applysuccess) or a [fail](#policy-applyfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | policy       |
| Activity      | apply        |
| Activity Type | policy-apply |
| Pretty Name   | Policy Apply |
| Legacy Name   |              |

policy-apply:success
--------------------

There are no fields for this activity type.


policy-apply:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |