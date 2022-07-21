ip-free
=======

Description
-----------
An IP was freed from use and is now available to reassign

The possible fields for this activity type will vary depending on whether the activity was a [success](#ip-freesuccess) or a [fail](#ip-freefail).

| Parameter     | Value   |
| ------------- | ------- |
| Subject       | ip      |
| Activity      | free    |
| Activity Type | ip-free |
| Pretty Name   | Ip Free |
| Legacy Name   |         |

ip-free:success
---------------

There are no fields for this activity type.


ip-free:fail
------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |