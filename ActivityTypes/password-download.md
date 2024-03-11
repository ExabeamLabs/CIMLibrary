password-download
=================

Description
-----------
A stored password object was downloaded

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | password          |
| Activity      | download          |
| Activity Type | password-download |
| Pretty Name   | Password Download |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-downloadsuccess) or a [fail](#password-downloadfail).


password-download:success
-------------------------

There are no fields for this activity type.


password-download:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |