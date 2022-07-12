vm_pool-endpoint-remove
=======================

Description
-----------
An endpoint instance was removed from the VM pool

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_pool-endpoint-removesuccess) or a [fail](#vm_pool-endpoint-removefail).

| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | vm_pool                 |
| Activity      | endpoint-remove         |
| Activity Type | vm_pool-endpoint-remove |
| Pretty Name   | Vm_pool Endpoint Remove |
| Legacy Name   |                         |

vm_pool-endpoint-remove:success
-------------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      |           | &#10003;      |

vm_pool-endpoint-remove:fail
----------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      |           | &#10003;      |