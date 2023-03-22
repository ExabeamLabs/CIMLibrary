clipboard-read
==============

Description
-----------
A request was made to read the content of the clipboard

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | clipboard      |
| Activity      | read           |
| Activity Type | clipboard-read |
| Pretty Name   | Clipboard Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#clipboard-readsuccess) or a [fail](#clipboard-readfail).


clipboard-read:success
----------------------

There are no fields for this activity type.


clipboard-read:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |