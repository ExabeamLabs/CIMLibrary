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

| Activity Type             | Field       | Status  | Core     | Detection | Informational |
| ------------------------- | ----------- | ------- | -------- | --------- | ------------- |
| app-activity              | application | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| app-login                 | src_ip      | Default |          | &#10003;  |               |
| cluster-modify            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| datacenter-modify         | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| datastore-create          | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| datastore-delete          | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| datastore-enable          | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| datastore-modify          | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| disk-attach               | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| disk-modify               | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| disk-remove               | application | Default |          |           | &#10003;      |
|                           | resource    | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| disk-scan                 | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| endpoint-authentication   | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | object      | Default |          |           | &#10003;      |
| endpoint-create           | application | Default |          |           | &#10003;      |
|                           | resource    | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| endpoint-login            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | object      | Default |          |           | &#10003;      |
| endpoint-logout           | application |         |          |           |               |
|                           | operation   |         |          |           |               |
|                           | object      |         |          |           |               |
| endpoint-modify           | application |         |          |           |               |
|                           | resource    |         |          |           |               |
|                           | operation   |         |          |           |               |
|                           | user        | Legacy  | &#10003; |           |               |
|                           | object      |         |          |           |               |
| endpoint-start            | application | Default |          |           | &#10003;      |
|                           | resource    | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| endpoint-stop             | application | Default |          |           | &#10003;      |
|                           | resource    | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| image-import              | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| log-clear                 | application |         |          |           |               |
|                           | operation   |         |          |           |               |
|                           | user        | Legacy  | &#10003; | &#10003;  |               |
|                           | object      |         |          |           |               |
| peripheral_storage-insert | application |         |          |           |               |
|                           | operation   |         |          |           |               |
|                           | user        | Legacy  | &#10003; | &#10003;  |               |
|                           | object      |         |          |           |               |
| peripheral_storage-remove | application |         |          |           |               |
|                           | operation   |         |          |           |               |
|                           | user        | Legacy  | &#10003; |           |               |
|                           | object      |         |          |           |               |
| policy-modify             | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| vm_host-create            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| vm_host-enable            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| vm_host-modify            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| vm_pool-modify            | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |
|                           | object      | Default |          |           | &#10003;      |
| vm_template-delete        | application | Default |          |           | &#10003;      |
|                           | operation   | Default |          |           | &#10003;      |
|                           | user        | Default |          | &#10003;  |               |

