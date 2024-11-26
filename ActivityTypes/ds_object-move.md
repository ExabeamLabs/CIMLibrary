ds_object-move
==============

Description
-----------
A directory service object moved to another location

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | ds_object      |
| Activity      | move           |
| Activity Type | ds_object-move |
| Pretty Name   | Ds_object Move |

Legacy Names
------------
| Success       | Fail |
| ------------- | ---- |
| ds-access<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-movesuccess) or a [fail](#ds_object-movefail).


ds_object-move:success
----------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| object_type        |      |           | &#10003;      |
| src_ds_object_ou   |      | &#10003;  |               |
| src_ds_object_name |      |           | &#10003;      |
| src_ds_object_dn   |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.