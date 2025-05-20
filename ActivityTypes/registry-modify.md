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

| Field                     | Core | Detection | Informational |
| ------------------------- | ---- | --------- | ------------- |
| old_registry_details_type |      | &#10003;  |               |
| old_registry_details      |      | &#10003;  |               |
| cid                       |      |           | &#10003;      |

registry-modify:fail
--------------------

| Field                     | Core | Detection | Informational |
| ------------------------- | ---- | --------- | ------------- |
| failure_code              |      | &#10003;  |               |
| old_registry_details_type |      | &#10003;  |               |
| failure_reason            |      | &#10003;  |               |
| old_registry_details      |      | &#10003;  |               |
| cid                       |      |           | &#10003;      |