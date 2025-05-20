registry-export
===============

Description
-----------
A registry key or value were exported

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | export          |
| Activity Type | registry-export |
| Pretty Name   | Registry Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-exportsuccess) or a [fail](#registry-exportfail).


registry-export:success
-----------------------

There are no fields for this activity type.


registry-export:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |