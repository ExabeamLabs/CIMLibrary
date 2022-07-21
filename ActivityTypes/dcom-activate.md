dcom-activate
=============

Description
-----------
An activation of DCOM application

The possible fields for this activity type will vary depending on whether the activity was a [success](#dcom-activatesuccess) or a [fail](#dcom-activatefail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | dcom          |
| Activity      | activate      |
| Activity Type | dcom-activate |
| Pretty Name   | Dcom Activate |
| Legacy Name   |               |

dcom-activate:success
---------------------

There are no fields for this activity type.


dcom-activate:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |