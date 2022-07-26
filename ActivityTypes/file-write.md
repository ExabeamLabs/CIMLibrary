file-write
==========

Description
-----------
A file was created or edited

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | file       |
| Activity      | write      |
| Activity Type | file-write |
| Pretty Name   | File Write |

Legacy Names
------------
| Success                     | Fail                        |
| --------------------------- | --------------------------- |
| file-write<br>usb-write<br> | file-write<br>usb-write<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-writesuccess) or a [fail](#file-writefail).


file-write:success
------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| is_dok |      | &#10003;  |               |

file-write:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| is_dok         |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |