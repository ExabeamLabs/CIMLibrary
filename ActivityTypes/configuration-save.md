configuration-save
==================

Description
-----------
Changes to the global configuration of an application or a program were saved

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | configuration      |
| Activity      | save               |
| Activity Type | configuration-save |
| Pretty Name   | Configuration Save |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-savesuccess) or a [fail](#configuration-savefail).


configuration-save:success
--------------------------

There are no fields for this activity type.


configuration-save:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |