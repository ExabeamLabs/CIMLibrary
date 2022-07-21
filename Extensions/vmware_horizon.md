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
| configuration-modify    | application     |         |          |           |               |
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
| folder-create           | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| folder-delete           | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| folder-modify           | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| policy-delete           | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| policy-modify           | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-create             | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-delete             | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| role-modify             | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| user-modify             | application     |         |          |           |               |
|                         | additional_info |         |          |           |               |
|                         | domain          | Legacy  |          |           | &#10003;      |
|                         | dest_host       | Legacy  |          |           | &#10003;      |
|                         | user            | Legacy  | &#10003; |           |               |
|                         | operation       |         |          |           |               |
|                         | object          |         |          |           |               |
| user-permission-modify  | application     |         |          |           |               |
|                         | additional_info |         |          |           |               |
|                         | domain          | Legacy  |          |           | &#10003;      |
|                         | dest_host       | Legacy  |          |           | &#10003;      |
|                         | user            | Legacy  | &#10003; |           |               |
|                         | operation       |         |          |           |               |
|                         | object          |         |          |           |               |
| vm_pool-create          | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-delete          | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-endpoint-add    | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-endpoint-remove | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |
| vm_pool-modify          | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | domain          | Default |          |           | &#10003;      |
|                         | dest_host       | Default |          | &#10003;  |               |
|                         | user            | Default |          | &#10003;  |               |
|                         | operation       | Default |          |           | &#10003;      |
|                         | object          | Default |          |           | &#10003;      |

