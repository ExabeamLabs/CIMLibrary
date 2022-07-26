dll-load
========

Description
-----------
A dll module was loaded into a process

Parameters
----------
| Parameter     | Value    |
| ------------- | -------- |
| Subject       | dll      |
| Activity      | load     |
| Activity Type | dll-load |
| Pretty Name   | Dll Load |

Legacy Names
------------
| Success          | Fail             |
| ---------------- | ---------------- |
| image-loaded<br> | image-loaded<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dll-loadsuccess) or a [fail](#dll-loadfail).


dll-load:success
----------------

There are no fields for this activity type.


dll-load:fail
-------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |