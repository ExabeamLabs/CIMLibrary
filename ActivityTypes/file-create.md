file-create
===========

Description
-----------
A file was created

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | create      |
| Activity Type | file-create |
| Pretty Name   | File Create |

Legacy Names
------------
| Success        | Fail           |
| -------------- | -------------- |
| file-write<br> | file-write<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-createsuccess) or a [fail](#file-createfail).


file-create:success
-------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| is_dok |      | &#10003;  |               |

file-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| is_dok         |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |