vmware horizon
==============

Expression
----------

product = "vmware horizon"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field           | Status  | Core     | Detection | Informational |
| ----------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-authentication      | src_ip          | Default |          | &#10003;  |               |
|                         | session_id      | Default |          |           | &#10003;      |
| configuration-modify    | app             |         |          |           |               |
|                         | additional_info |         |          |           |               |
|                         | domain          |         |          |           |               |
|                         | dest_host       |         |          |           |               |
|                         | user            |         |          |           |               |
|                         | operation       |         |          |           |               |
|                         | object          |         |          |           |               |
| endpoint-login          | user_id         | Default |          |           | &#10003;      |
|                         | resource        | Default |          |           | &#10003;      |
|                         | dest_ip         | Default |          | &#10003;  |               |
|                         | object_id       | Default |          |           | &#10003;      |
| folder-create           | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| folder-delete           | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| folder-modify           | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| policy-delete           | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| policy-modify           | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-create             | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-delete             | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-modify             | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| user-modify             | app             |         |          |           |               |
|                         | additional_info |         |          |           |               |
|                         | domain          | Legacy  |          |           | &#10003;      |
|                         | dest_host       | Legacy  |          |           | &#10003;      |
|                         | user            | Legacy  | &#10003; |           |               |
|                         | operation       |         |          |           |               |
|                         | object          |         |          |           |               |
| user-permission-modify  | app             |         |          |           |               |
|                         | additional_info |         |          |           |               |
|                         | domain          | Legacy  |          |           | &#10003;      |
|                         | dest_host       | Legacy  |          |           | &#10003;      |
|                         | user            | Legacy  | &#10003; |           |               |
|                         | operation       |         |          |           |               |
|                         | object          |         |          |           |               |
| vm_pool-create          | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-delete          | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-endpoint-add    | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-endpoint-remove | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-modify          | app             | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |

