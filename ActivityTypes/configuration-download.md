configuration-download
======================

Description
-----------
The global configuration of an application or a program was downloaded

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | configuration          |
| Activity      | download               |
| Activity Type | configuration-download |
| Pretty Name   | Configuration Download |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-downloadsuccess) or a [fail](#configuration-downloadfail).


configuration-download:success
------------------------------

There are no fields for this activity type.


configuration-download:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |