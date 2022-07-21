vm_pool-delete
==============

Description
-----------
A VM pool was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_pool-deletesuccess) or a [fail](#vm_pool-deletefail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_pool        |
| Activity      | delete         |
| Activity Type | vm_pool-delete |
| Pretty Name   | Vm_pool Delete |
| Legacy Name   |                |

vm_pool-delete:success
----------------------

There are no fields for this activity type.


vm_pool-delete:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |