vm_pool-endpoint-add
====================

Description
-----------
An endpoint instance was added to the VM pool

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_pool-endpoint-addsuccess) or a [fail](#vm_pool-endpoint-addfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | vm_pool              |
| Activity      | endpoint-add         |
| Activity Type | vm_pool-endpoint-add |
| Pretty Name   | Vm_pool Endpoint Add |
| Legacy Name   |                      |

vm_pool-endpoint-add:success
----------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| dest_host |      |           | &#10003;      |

vm_pool-endpoint-add:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| dest_host      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |