registry-read
=============

Description
-----------
A registry key or value were read

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | registry      |
| Activity      | read          |
| Activity Type | registry-read |
| Pretty Name   | Registry Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-readsuccess) or a [fail](#registry-readfail).


registry-read:success
---------------------

There are no fields for this activity type.


registry-read:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |