vm_template-create
==================

Description
-----------
A VM template was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#vm_template-createsuccess) or a [fail](#vm_template-createfail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | vm_template        |
| Activity      | create             |
| Activity Type | vm_template-create |
| Pretty Name   | Vm_template Create |
| Legacy Name   |                    |

vm_template-create:success
--------------------------

There are no fields for this activity type.


vm_template-create:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |