ds_object-restore
=================

Description
-----------
A directory service object was restored

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | ds_object         |
| Activity      | restore           |
| Activity Type | ds_object-restore |
| Pretty Name   | Ds_object Restore |

Legacy Names
------------
| Success       | Fail |
| ------------- | ---- |
| ds-access<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-restoresuccess) or a [fail](#ds_object-restorefail).


ds_object-restore:success
-------------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| object_type        |      |           | &#10003;      |
| src_ds_object_ou   |      |           |               |
| src_ds_object_name |      |           |               |
| src_ds_object_dn   |      |           |               |

A failure activity is not currently supported for this activity-type.