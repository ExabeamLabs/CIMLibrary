network-close
=============

Description
-----------
A network session was terminated

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-closesuccess) or a [fail](#network-closefail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | network       |
| Activity      | close         |
| Activity Type | network-close |
| Pretty Name   | Network Close |
| Legacy Name   |               |

network-close:success
---------------------

There are no fields for this activity type.


network-close:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |