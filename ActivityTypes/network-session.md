network-session
===============

Description
-----------
A representation of an entire network session

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-sessionsuccess) or a [fail](#network-sessionfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | network         |
| Activity      | session         |
| Activity Type | network-session |
| Pretty Name   | Network Session |
| Legacy Name   |                 |

network-session:success
-----------------------

There are no fields for this activity type.


network-session:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |