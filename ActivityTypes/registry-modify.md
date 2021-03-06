registry-modify
===============

Description
-----------
The content or configuration of a registry object was modified

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | modify          |
| Activity Type | registry-modify |
| Pretty Name   | Registry Modify |

Legacy Names
------------
| Success            | Fail               |
| ------------------ | ------------------ |
| registry-write<br> | registry-write<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-modifysuccess) or a [fail](#registry-modifyfail).


registry-modify:success
-----------------------

There are no fields for this activity type.


registry-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |