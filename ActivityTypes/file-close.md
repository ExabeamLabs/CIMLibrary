file-close
==========

Description
-----------
A file was closed

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | file       |
| Activity      | close      |
| Activity Type | file-close |
| Pretty Name   | File Close |

Legacy Names
------------
| Success        | Fail           |
| -------------- | -------------- |
| file-close<br> | file-close<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-closesuccess) or a [fail](#file-closefail).


file-close:success
------------------

There are no fields for this activity type.


file-close:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |