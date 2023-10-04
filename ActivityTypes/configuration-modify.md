configuration-modify
====================

Description
-----------
The global configuration of an application or a program was modified

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | configuration        |
| Activity      | modify               |
| Activity Type | configuration-modify |
| Pretty Name   | Configuration Modify |

Legacy Names
------------
| Success           | Fail              |
| ----------------- | ----------------- |
| config-change<br> | config-change<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-modifysuccess) or a [fail](#configuration-modifyfail).


configuration-modify:success
----------------------------

| Field | Core | Detection | Informational |
| ----- | ---- | --------- | ------------- |
| cid   |      |           | &#10003;      |

configuration-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| cid            |      |           | &#10003;      |