dll-unload
==========

Description
-----------
A dll module was unloaded from a process

The possible fields for this activity type will vary depending on whether the activity was a [success](#dll-unloadsuccess) or a [fail](#dll-unloadfail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | dll        |
| Activity      | unload     |
| Activity Type | dll-unload |
| Pretty Name   | Dll Unload |
| Legacy Name   |            |

dll-unload:success
------------------

There are no fields for this activity type.


dll-unload:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |