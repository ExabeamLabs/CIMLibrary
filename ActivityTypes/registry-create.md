registry-create
===============

Description
-----------
A registry object was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | create          |
| Activity Type | registry-create |
| Pretty Name   | Registry Create |

Legacy Names
------------
| Success            | Fail               |
| ------------------ | ------------------ |
| registry-write<br> | registry-write<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-createsuccess) or a [fail](#registry-createfail).


registry-create:success
-----------------------

There are no fields for this activity type.


registry-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |