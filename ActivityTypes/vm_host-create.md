vm_host-create
==============

Description
-----------
A VM host was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_host-createsuccess) or a [fail](#vm_host-createfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | vm_host        |
| Activity      | create         |
| Activity Type | vm_host-create |
| Pretty Name   | Vm_host Create |
| Legacy Name   |                |

vm_host-create:success
----------------------

There are no fields for this activity type.


vm_host-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |