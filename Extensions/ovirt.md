ovirt
=====

Expression
----------

product = "ovirt"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type             | Field              | Status  | Core     | Detection | Informational |
| ------------------------- | ------------------ | ------- | -------- | --------- | ------------- |
| app-activity              | app                | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| app-login                 | src_ip             | Default |          | &#10003;  |               |
| cluster-modify            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| datacenter-modify         | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| datastore-create          | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| datastore-delete          | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| datastore-enable          | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| datastore-modify          | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| disk-attach               | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| disk-modify               | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| disk-remove               | app                | Default |          |           | &#10003;      |
|                           | resource           | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| disk-scan                 | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| endpoint-authentication   | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | object             | Default |          |           | &#10003;      |
| endpoint-create           | app                | Default |          |           | &#10003;      |
|                           | resource           | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| endpoint-login            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | object             | Default |          |           | &#10003;      |
| endpoint-logout           | app                |         |          |           |               |
|                           | operation          |         |          |           |               |
|                           | object             |         |          |           |               |
| endpoint-modify           | app                |         |          |           |               |
|                           | resource           |         |          |           |               |
|                           | operation          |         |          |           |               |
|                           | user               | Legacy  | &#10003; |           |               |
|                           | object             |         |          |           |               |
| endpoint-start            | app                | Default |          |           | &#10003;      |
|                           | resource           | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| endpoint-stop             | app                | Default |          |           | &#10003;      |
|                           | resource           | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| image-import              | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| log-clear                 | app                |         |          |           |               |
|                           | operation          |         |          |           |               |
|                           | user               | Legacy  | &#10003; | &#10003;  |               |
|                           | object             |         |          |           |               |
| peripheral_storage-insert | app                |         |          |           |               |
|                           | device_product     |         |          |           | &#10003;      |
|                           | device_pid         |         |          |           | &#10003;      |
|                           | device_description |         |          |           | &#10003;      |
|                           | device_class       |         |          |           | &#10003;      |
|                           | device_vendor      |         |          |           | &#10003;      |
|                           | device_vid         |         |          |           | &#10003;      |
|                           | operation          |         |          |           |               |
|                           | user               | Legacy  | &#10003; | &#10003;  |               |
|                           | object             |         |          |           |               |
| peripheral_storage-remove | app                |         |          |           |               |
|                           | device_product     |         |          |           | &#10003;      |
|                           | device_pid         |         |          |           | &#10003;      |
|                           | device_description |         |          |           | &#10003;      |
|                           | device_class       |         |          |           | &#10003;      |
|                           | device_vendor      |         |          |           | &#10003;      |
|                           | device_vid         |         |          |           | &#10003;      |
|                           | operation          |         |          |           |               |
|                           | user               | Legacy  | &#10003; |           |               |
|                           | object             |         |          |           |               |
| policy-modify             | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| vm_host-create            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| vm_host-enable            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| vm_host-modify            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| vm_pool-modify            | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |
|                           | object             | Default |          |           | &#10003;      |
| vm_template-delete        | app                | Default |          |           | &#10003;      |
|                           | operation          | Default |          |           | &#10003;      |
|                           | user               | Default |          | &#10003;  |               |

