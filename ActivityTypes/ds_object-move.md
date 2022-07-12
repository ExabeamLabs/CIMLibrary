ds_object-move
==============

Description
-----------
A directory service object moved to another location

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-movesuccess) or a [fail](#ds_object-movefail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | ds_object      |
| Activity      | move           |
| Activity Type | ds_object-move |
| Pretty Name   | Ds_object Move |
| Legacy Name   |                |

ds_object-move:success
----------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ds_object_ou   |      | &#10003;  |               |
| src_ds_object_name |      |           | &#10003;      |
| src_ds_object_dn   |      | &#10003;  |               |

ds_object-move:fail
-------------------

There are no fields for this activity type.
