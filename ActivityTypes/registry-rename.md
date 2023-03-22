registry-rename
===============

Description
-----------
A registry key or value were renamed

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | rename          |
| Activity Type | registry-rename |
| Pretty Name   | Registry Rename |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-renamesuccess) or a [fail](#registry-renamefail).


registry-rename:success
-----------------------

There are no fields for this activity type.


registry-rename:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |